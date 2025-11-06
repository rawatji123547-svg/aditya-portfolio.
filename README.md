<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aditya Rawat - B.Tech CSE Student Portfolio</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font import and application */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            @apply bg-gray-50 text-gray-800;
            scroll-behavior: smooth;
        }
        /* Style for smooth hover effect on cards */
        .portfolio-card {
            transition: all 0.3s ease-in-out;
        }
        .portfolio-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="antialiased">

    <!-- Header & Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center max-w-7xl">
            <a href="#" class="text-2xl font-extrabold text-indigo-600 tracking-tight">AR</a>
            <nav class="space-x-4">
                <a href="#about" class="text-gray-600 hover:text-indigo-600 transition duration-150 font-medium">About</a>
                <a href="#projects" class="text-gray-600 hover:text-indigo-600 transition duration-150 font-medium">Projects</a>
                <a href="#contact" class="text-gray-600 hover:text-indigo-600 transition duration-150 font-medium">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="bg-indigo-700 text-white py-16 md:py-24">
        <div class="container mx-auto px-4 max-w-7xl text-center">
            <!-- Replace with your profile image URL or use a placeholder -->
            <img class="w-24 h-24 rounded-full mx-auto mb-6 object-cover border-4 border-indigo-400 shadow-xl" 
                 src="https://placehold.co/150x150/ffffff/374151?text=AR" 
                 alt="Profile Picture" 
                 onerror="this.src='https://placehold.co/150x150/ffffff/374151?text=AR'">
            
            <h1 class="text-4xl md:text-6xl font-extrabold mb-3 leading-tight">
                Aditya Rawat
            </h1>
            <p class="text-xl md:text-2xl font-light mb-8 opacity-90">
                B.Tech CSE Student | C/C++ Enthusiast | Collaborative Problem Solver
            </p>
            <a href="#projects" class="inline-block bg-white text-indigo-700 font-bold py-3 px-8 rounded-full shadow-lg hover:bg-indigo-100 transition duration-300 transform hover:scale-105">
                View Academic Projects
            </a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-3xl font-bold text-center mb-12">About Me</h2>
            <div class="text-lg leading-relaxed text-gray-700 space-y-4">
                <p>
                    I am an enthusiastic and goal-driven **B.Tech CSE student** in my second year at **Graphic Era Hill University**. I am currently focused on mastering the foundational principles of computer science and applying them practically through academic projects and coding challenges.
                </p>
                <p>
                    I possess strong foundational knowledge in **C and C++**, which I use for implementing data structures and problem-solving. Beyond technical skills, I pride myself on excellent **communication** and **teamwork abilities**, which ensure I contribute effectively to collaborative environments. My ultimate career goal is to join a reputable **IT company** where I can contribute to complex engineering challenges and continuously grow my technical expertise.
                </p>
                <div class="mt-8">
                    <h3 class="text-xl font-semibold mb-4 text-indigo-600">Key Skills</h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-3 py-1 rounded-full">C/C++ Programming</span>
                        <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-3 py-1 rounded-full">Teamwork & Collaboration</span>
                        <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-3 py-1 rounded-full">Effective Communication</span>
                        <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-3 py-1 rounded-full">Data Structures</span>
                        <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-3 py-1 rounded-full">Object-Oriented Programming (OOP)</span>
                        <span class="bg-indigo-100 text-indigo-800 text-sm font-medium px-3 py-1 rounded-full">Problem Solving</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 md:py-24 bg-gray-50">
        <div class="container mx-auto px-4 max-w-7xl">
            <h2 class="text-3xl font-bold text-center mb-12">Academic & Personal Projects</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                
                <!-- Project Card 1: University Timetable Management System -->
                <div class="portfolio-card bg-white rounded-xl shadow-lg overflow-hidden border border-gray-100">
                    <img class="w-full h-48 object-cover" 
                         src="https://placehold.co/600x400/2563eb/ffffff?text=Timetable+System" 
                         alt="Timetable Management System Thumbnail">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-indigo-600 mb-2">University Timetable Management System</h3>
                        <p class="text-gray-600 mb-4 text-sm">
                            A command-line application designed to efficiently schedule classes, manage faculty availability, and prevent timetable conflicts using algorithmic scheduling.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-blue-100 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded-full">C++</span>
                            <span class="bg-green-100 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded-full">Algorithmic Design</span>
                            <span class="bg-red-100 text-red-800 text-xs font-medium px-2.5 py-0.5 rounded-full">File Handling</span>
                        </div>
                        <a href="#" target="_blank" class="text-indigo-500 hover:text-indigo-700 font-semibold text-sm flex items-center">
                            View Project (or Code)
                            <svg class="ml-1 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                        </a>
                    </div>
                </div>

                <!-- Project Card 2: Disaster Management System -->
                <div class="portfolio-card bg-white rounded-xl shadow-lg overflow-hidden border border-gray-100">
                    <img class="w-full h-48 object-cover" 
                         src="https://placehold.co/600x400/10b981/ffffff?text=Disaster+Model" 
                         alt="Disaster Management System Thumbnail">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-indigo-600 mb-2">Disaster Management System (Simulation)</h3>
                        <p class="text-gray-600 mb-4 text-sm">
                            A console-based simulation tool that models resource allocation, critical communication protocols, and optimized emergency response routes during a crisis scenario.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-green-100 text-green-800 text-xs font-medium px-2.5 py-0.5 rounded-full">C Language</span>
                            <span class="bg-yellow-100 text-yellow-800 text-xs font-medium px-2.5 py-0.5 rounded-full">Graph Data Structure</span>
                            <span class="bg-gray-100 text-gray-800 text-xs font-medium px-2.5 py-0.5 rounded-full">Simulation Logic</span>
                        </div>
                        <a href="#" target="_blank" class="text-indigo-500 hover:text-indigo-700 font-semibold text-sm flex items-center">
                            View Project (or Code)
                            <svg class="ml-1 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                        </a>
                    </div>
                </div>

                <!-- Project Card 3: Personal Portfolio Site (Created for breadth) -->
                <div class="portfolio-card bg-white rounded-xl shadow-lg overflow-hidden border border-gray-100">
                    <img class="w-full h-48 object-cover" 
                         src="https://placehold.co/600x400/f59e0b/ffffff?text=Website+Development" 
                         alt="Web Dev Project Thumbnail">
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-indigo-600 mb-2">Foundational Web Development Site</h3>
                        <p class="text-gray-600 mb-4 text-sm">
                            A simple, responsive landing page developed to showcase initial web development skills, focusing on semantic structure and clean, modern design principles.
                        </p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-yellow-100 text-yellow-800 text-xs font-medium px-2.5 py-0.5 rounded-full">HTML5</span>
                            <span class="bg-red-100 text-red-800 text-xs font-medium px-2.5 py-0.5 rounded-full">CSS3</span>
                            <span class="bg-blue-100 text-blue-800 text-xs font-medium px-2.5 py-0.5 rounded-full">Responsive Design</span>
                        </div>
                        <a href="#" target="_blank" class="text-indigo-500 hover:text-indigo-700 font-semibold text-sm flex items-center">
                            View Demo
                            <svg class="ml-1 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path></svg>
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4 max-w-2xl text-center">
            <h2 class="text-3xl font-bold mb-4">Get In Touch</h2>
            <p class="text-lg text-gray-700 mb-8">
                I'm actively looking for opportunities and internships in the IT field. Feel free to connect to discuss my projects or potential roles!
            </p>
            
            <a href="mailto:rawataditya598@gmail.com" class="inline-block bg-indigo-600 text-white font-bold py-3 px-8 rounded-full shadow-xl hover:bg-indigo-700 transition duration-300 transform hover:scale-105">
                Email Me: rawataditya598@gmail.com
            </a>

            <div class="mt-12 flex justify-center space-x-6">
                <!-- You can replace these with links to your GitHub and LinkedIn profiles -->
                <a href="#" target="_blank" class="text-gray-500 hover:text-indigo-600 transition duration-300">
                    <!-- Placeholder for GitHub Icon -->
                    <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.082-.742.083-.727.083-.727 1.205.084 1.839 1.237 1.839 1.237 1.07 1.835 2.809 1.305 3.493.998.108-.776.417-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.468-2.381 1.236-3.221-.124-.303-.535-1.524.118-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.046.138 3.003.404 2.292-1.552 3.301-1.23 3.301-1.23.653 1.653.242 2.873.118 3.176.77.84 1.236 1.911 1.236 3.221 0 4.609-2.807 5.624-5.479 5.923.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.565 21.802 24 17.301 24 12c0-6.627-5.373-12-12-12z"/></svg>
                </a>
                <a href="#" target="_blank" class="text-gray-500 hover:text-indigo-600 transition duration-300">
                    <!-- Placeholder for LinkedIn Icon -->
                    <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.555-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 max-w-7xl text-center text-sm">
            <p>&copy; 2025 Aditya Rawat. Built with <span class="text-indigo-400">&hearts;</span> and Tailwind CSS.</p>
            <div class="mt-2 text-gray-400">
                <a href="#hero" class="hover:text-indigo-400 transition duration-150">Back to Top</a>
            </div>
        </div>
    </footer>

</body>
</html>

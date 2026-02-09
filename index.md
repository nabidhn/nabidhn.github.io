<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nabid Hasan | Terminal Portfolio</title>
    <style>
        :root {
            --term-bg: #1a1b1e;
            --term-green: #a6e22e;
            --term-blue: #66d9ef;
            --term-dim: #94a3b8;
            --term-white: #f8f8f2;
        }

        body {
            background-color: var(--term-bg);
            color: var(--term-white);
            font-family: 'Fira Code', 'Courier New', monospace;
            margin: 0;
            padding: 2rem;
            line-height: 1.6;
        }

        .terminal-nav {
            border-bottom: 1px dashed var(--term-dim);
            padding-bottom: 1rem;
            margin-bottom: 2rem;
            display: flex;
            justify-content: space-between;
        }

        .nav-links a {
            color: var(--term-blue);
            text-decoration: none;
            margin-right: 1.5rem;
        }

        .nav-links a:hover { text-decoration: underline; }

        .prompt { color: var(--term-green); font-weight: bold; }
        
        .hero h1 { font-size: 2.5rem; color: var(--term-green); margin: 0; }
        
        .tagline { color: var(--term-dim); font-style: italic; margin-bottom: 2rem; }

        .about-section {
            max-width: 900px;
            border-left: 2px solid var(--term-green);
            padding-left: 1.5rem;
            margin-bottom: 3rem;
        }

        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .skill-card {
            background: #25262b;
            padding: 1.5rem;
            border-radius: 4px;
            border: 1px solid #373a40;
        }

        .skill-card h3 { color: var(--term-blue); margin-top: 0; }
        
        .tech-list {
            list-style: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .tech-tag {
            background: #373a40;
            font-size: 0.8rem;
            padding: 2px 8px;
            border-radius: 3px;
        }

        .github-btn {
            display: inline-block;
            background: var(--term-green);
            color: black;
            padding: 0.5rem 1rem;
            text-decoration: none;
            font-weight: bold;
            border-radius: 4px;
            margin-top: 1rem;
        }
    </style>
</head>
<body>

    <nav class="terminal-nav">
        <div class="nav-links">
            <a href="projects.md">./Projects</a>
            <a href="contact.md">./Contact</a>
        </div>
        <div class="status">
            <span class="prompt">STATUS:</span> ACTIVE_RESEARCHER
        </div>
    </nav>

    <header class="hero">
        <h1>./Nabid Hasan's Portfolio</h1>
        <p class="tagline"> Wireless Communications, Signal Processing, Machine Learning, CLoud Technologies</p>
        
        <div class="about-section">
            <p><span class="prompt">guest@tuni:~$</span> cat intro.txt</p>
            <p>
               👋 I’m an MSc student in Wireless Communication and RF Systems at Tampere University, specializing in GNSS positioning, 5G/Cloud RAN, and Machine Learning for communication systems.

                I enjoy working across the full stack of modern telecom systems. This includes physical layer fundamentals—such as Modulation, Channel Coding, and Equalization—as well as the deployment and                             optimization of Cloud RAN (vRAN) environments, focusing on Radio Resource Management and Network Security. On the positioning side, I apply practical GNSS techniques like PVT estimation, RTK/PPP, and                   interference detection using tools like RTKLIB.

                I am also proficient in Python, MATLAB, and C/C++. I am experienced in managing Linux environments (RedHat/Debian) and automating infrastructure with Ansible and Terraform. I specialize in deploying                    containerized applications via Docker and Kubernetes across AWS, Azure, GCP and CSC cloud platforms, utilizing MLOps and CI/CD pipelines to move services from experimentation to reliable production.
            </p>
            <a href="#" class="github-btn">View on GitHub</a>
        </div>
    </header>

    <main class="grid-container">
        <div class="skill-card">
            <h3>📡 Wireless & RF</h3>
            <p> Radio Access Network, 5G physical layers and GNSS </p>
            <div class="tech-list">
                <span class="tech-tag">5G NR</span>
                <span class="tech-tag">OFDM</span>
                <span class="tech-tag">RTK/PPP</span>
                <span class="tech-tag">RTKLIB</span>
                <span class="tech-tag">GPS</span>
                <span class="tech-tag">GNSS Receiver</span>
                <span class="tech-tag">MIMO</span>
                <span class="tech-tag">Cloud RAN</span>
            </div>
        </div>

        <div class="skill-card">
            <h3>☁️ Cloud & MLOps</h3>
            <p>Automating infrastructure and deploying containerized applications.</p>
            <div class="tech-list">
                <span class="tech-tag">Kubernetes</span>
                <span class="tech-tag">Docker</span>
                <span class="tech-tag">Terraform</span>
                <span class="tech-tag">Ansible</span>
                <span class="tech-tag">CI/CD</span>
            </div>
        </div>

        <div class="skill-card">
            <h3>💻 Programming</h3>
            <p>Proficient in Simulation and Data Analysis.</p>
            <div class="tech-list">
                <span class="tech-tag">Python</span>
                <span class="tech-tag">MATLAB</span>
                <span class="tech-tag">C/C++</span>
                <span class="tech-tag">Bash Scripting</span>
            </div>
        </div>
    </main>

    <footer style="margin-top: 4rem; color: var(--term-dim); font-size: 0.8rem; text-align: center;">
        <p>Built with <span style="color: #e06c75;">&hearts;</span> and Monospace Typography</p>
    </footer>

</body>
</html>





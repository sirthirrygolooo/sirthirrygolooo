<div class="container">
    <header>
        <h1>👋 jb_frhl, better known as SirThirrygolooo</h1>
        <p class="subtitle">Computer Science Student | Security Explorer | AI Enthusiast</p>
        <p>Pushing boundaries where code meets chaos. Currently studying at <strong>Université de Franche-Comté</strong>.</p>
    </header>
    <!-- les stateus -->
    <div class="stats">
        <div class="stat-card">
            <h3>GitHub Stats</h3>
            <img src="https://github-readme-stats.vercel.app/api?username=sirthirrygolooo&theme=tokyonight&show_icons=true&hide_border=true&count_private=true" alt="Stats">
        </div>
        <div class="stat-card">
            <h3>Top Languages</h3>
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sirthirrygolooo&theme=tokyonight&show_icons=true&hide_border=true&layout=compact" alt="Top Langs">
        </div>
        <div class="stat-card">
            <h3>Streak</h3>
            <img src="https://streak-stats.demolab.com?user=sirthirrygolooo&theme=tokyonight&hide_border=true" alt="Streak">
        </div>
    </div>
    <!-- À propos -->
    <div class="section">
        <h2>🔍 About Me</h2>
        <p>Passionate about <strong>IT security</strong> and <strong>AI experimentation</strong>. I love dissecting systems, automating tasks, and building things that break (or fix) other things. Currently diving deep into:</p>
        <div class="skills">
            <span class="skill">Java/Python</span>
            <span class="skill">Machine Learning</span>
            <span class="skill">Security breaching (at least I'm trying)</span>
            <span class="skill">Javascript</span>
            <span class="skill">VueJS</span>
            <span class="skill">Astro</span>
        </div>
    </div>
    <!-- liens projets -->
    <div class="section">
        <h2>💻 Featured Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>1</h3>
                <p>Faudra compléter</p>
                <a href="#">→ View Code</a>
            </div>
            <div class="project">
                <h3>2</h3>
                <p>Tout pareil</p>
                <a href="#">→ View Code</a>
            </div>
        </div>
    </div>
    <!-- plus d'infos / portfolio / cv ?-->
    <div class="section">
        <h2>📬 Get In Touch</h2>
        <p>Find me on:</p>
        <p>
            <a href="https://github.com/sirthirrygolooo">GitHub for studies</a> |
            <a href="mailto:jb.froehly@proton.me">Email</a> |
            <a href="#">LinkedIn</a>
        </p>
    </div>
    <footer>
        <p>Last updated: <script>document.write(new Date().toLocaleDateString())</script></p>
        <p>Made with 💖 and ⌨️ by SirThirryGolooo</p>
    </footer>
</div>
<style>
    :root {
        --bg: #1a1b27;
        --primary: #7aa2f7;
        --secondary: #449dab;
        --accent: #bb9af7;
        --text: #c0caf5;
        --card: #24283b;
    }
    body {
        font-family: 'Segoe UI', sans-serif;
        background-color: var(--bg);
        color: var(--text);
        margin: 0;
        padding: 0;
        line-height: 1.6;
    }
    .container {
        max-width: 1000px;
        margin: 0 auto;
        padding: 2rem;
    }
    header {
        text-align: center;
        margin-bottom: 2rem;
        border-bottom: 1px solid var(--accent);
        padding-bottom: 1rem;
    }
    h1 {
        color: var(--primary);
        font-size: 2.5rem;
        margin-bottom: 0.5rem;
    }
    .subtitle {
        color: var(--secondary);
        font-style: italic;
    }
    .stats {
        display: flex;
        justify-content: space-around;
        flex-wrap: wrap;
        gap: 1rem;
        margin: 2rem 0;
    }
    .stat-card {
        background: var(--card);
        border-radius: 10px;
        padding: 1rem;
        flex: 1;
        min-width: 250px;
    }
    .section {
        margin: 2rem 0;
        background: var(--card);
        border-radius: 10px;
        padding: 1.5rem;
    }
    .section h2 {
        color: var(--primary);
        border-bottom: 1px solid var(--accent);
        padding-bottom: 0.5rem;
    }
    .skills {
        display: flex;
        flex-wrap: wrap;
        gap: 0.5rem;
    }
    .skill {
        background: #363a4f;
        padding: 0.3rem 0.8rem;
        border-radius: 20px;
        font-size: 0.9rem;
    }
    .projects {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        gap: 1rem;
    }
    .project {
        background: #2d3147;
        padding: 1rem;
        border-radius: 8px;
        border-left: 4px solid var(--primary);
    }
    footer {
        text-align: center;
        margin-top: 2rem;
        color: #737994;
        font-size: 0.9rem;
    }
    a {
        color: var(--secondary);
        text-decoration: none;
    }
    a:hover {
        text-decoration: underline;
    }
    /* le glow c'est based */
    @keyframes glow {
        from { text-shadow: 0 0 5px var(--primary); }
        to { text-shadow: 0 0 15px var(--primary), 0 0 20px var(--accent); }
    }
    h1 {
        animation: glow 2s ease-in-out infinite alternate;
    }
</style>

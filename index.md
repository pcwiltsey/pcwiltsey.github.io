---
layout: default
title: "Paul Wiltsey - DevSecOps Engineer"
subtitle: "Senior DevSecOps Engineer"
---

<section id="about">
    <h2>About</h2>
    <p>Experienced DevSecOps engineer with a passion for security, automation, and efficient infrastructure. Skilled in cloud platforms, CI/CD pipelines, and secure development practices.</p>
</section>

<section id="projects" class="two-column">
    <h2>Projects</h2>
    <div class="project">
        <h3>Project 1</h3>
        <p>Description of your first project. Include technologies used and key achievements.</p>
    </div>
    <div class="project">
        <h3>Project 2</h3>
        <p>Description of your second project. Highlight security implementations or DevOps improvements.</p>
    </div>
</section>

<section id="resume">
    <h2>Resume</h2>
    {% capture resume_content %}{% include resume.md %}{% endcapture %}{{ resume_content | markdownify }}
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: pwiltsey@gmail.com</p>
    <p>LinkedIn: <a href="https://linkedin.com/in/pwiltsey">linkedin.com/in/pwiltsey</a></p>
    <p>GitHub: <a href="https://github.com/pcwiltsey">github.com/pcwiltsey</a></p>
</section>

---
layout: default
---

# Welcome

[LinkedIn](https://www.linkedin.com/in/owen-williams-6768071b7)

[About me](./Aboutme.md).

<html>
<head>
    <title>Dropdown Menu</title>
    <style>
        /* Styles for the dropdown menu (similar to previous examples) */
        /* ... */
    </style>
</head>
<body>
    <div class="dropdown">
        <button class="dropbtn">Posts</button>
        <div class="dropdown-content">
            <a href="https://owenw1lliams.github.io/posts.html">Posts</a>
            <a href="https://owenw1lliams.github.io/posts.html">Posts</a>
            <!-- Add more links to your blog posts with their respective URLs -->
        </div>
    </div>

    <script>
        // JavaScript to handle navigation when an option is selected
        document.addEventListener('DOMContentLoaded', function () {
            var dropdown = document.querySelector('.dropdown');
            var links = dropdown.querySelectorAll('a');

            links.forEach(function (link) {
                link.addEventListener('click', function (event) {
                    // Prevent the default behavior of the link (e.g., navigating away)
                    event.preventDefault();

                    // Get the href attribute of the clicked link
                    var href = link.getAttribute('href');

                    // Redirect to the specified URL
                    window.location.href = href;
                });
            });
        });
    </script>
</body>
</html>



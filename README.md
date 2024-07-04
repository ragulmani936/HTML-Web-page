# HTML-Web-page

## PROGRAM:

### index.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ABC College</title>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="College Logo">
        <h1>Name</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Welcome to ABC College</h2>
            <p>Our college is committed to providing excellent education and fostering the personal and professional growth of our students. We offer a variety of programs in Arts, Science, and Commerce, led by a dedicated faculty in a supportive learning environment.</p>
        </section>
    </main>
</body>
</html>
~~~

### Academics.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics - College Name</title>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="College Logo">
        <h1>ABC College</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Academic Departments</h2>
            <ul>
                <li>Science
                    <ul>
                        <li><a href="computer-science.html">Computer Science</a></li>
                        <li><a href="mathematics.html">Mathematics</a></li>
                    </ul>
                </li>
                <li>Arts
                    <ul>
                        <li><a href="english.html">English</a></li>
                        <li><a href="sociology.html">Sociology</a></li>
                    </ul>
                </li>
                <li>Commerce
                    <ul>
                        <li><a href="economics.html">Economics</a></li>
                        <li><a href="business-management.html">Business Management</a></li>
                    </ul>
                </li>
            </ul>
        </section>
    </main>
</body>
</html>
~~~

### Admission.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission - College Name</title>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="College Logo">
        <h1>ABC College</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Admission Form</h2>
            <form>
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>

                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required><br>


                
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br>

                <label for="course">Course Interested:</label>
                <select id="course" name="course">
                    <option value="computer-science">Computer Science</option>
                    <option value="mathematics">Mathematics</option>
                    <option value="english">English</option>
                    <option value="sociology">Sociology</option>
                    <option value="economics">Economics</option>
                    <option value="business-management">Business Management</option>
                </select><br>

                <label for="address">Address:</label>
                <textarea id="address" name="address" required></textarea><br>

                <button type="submit">Submit</button>
            </form>
        </section>
    </main>
</body>
</html>
~~~

### Gallery.html:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - ABC College</title>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="College Logo">
        <h1>College Name</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="academics.html">Academics</a></li>
                <li><a href="admission.html">Admission</a></li>
                <li><a href="gallery.html">Gallery</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2>Gallery</h2>
            <div>
                <img src="gallery1.jpg" alt="Gallery Image 1">
                <img src="gallery2.jpg" alt="Gallery Image 2">
                <img src="gallery3.jpg" alt="Gallery Image 3">
                <img src="gallery4.jpg" alt="Gallery Image 4">
            </div>
        </section>
    </main>
</body>
</html>
~~~

## OUPUT:

### Home:

![home](https://github.com/ragulmani936/HTML-Web-page/assets/94881918/c11fc1ff-5456-4851-84ca-a55dc673227f)

### Academics:

![academics](https://github.com/ragulmani936/HTML-Web-page/assets/94881918/8e74cdd1-ea95-4c01-b51a-8936603cc399)

### Admission:

![admission](https://github.com/ragulmani936/HTML-Web-page/assets/94881918/5157131c-1ce0-4dbe-be02-cf6e1e58c54b)

### Gallery:

![gallery](https://github.com/ragulmani936/HTML-Web-page/assets/94881918/c81c406a-13e2-4d94-840d-d3e337a2583d)

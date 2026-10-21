Assignment 3.2 — Images in HTML
1. Aim
To add images to a personal portfolio webpage using the HTML <img> tag, provide meaningful alternative text for accessibility, and verify that all images load correctly in a browser.

2. Project Folder Structure
Create your project with the following structure. Keep all three image files inside the images folder.

Assignment-3.2/

index.html

images/

profile.jpg

coding.jpg

hobby.jpg

Use your own photographs or suitable images, and rename them to match these filenames. The filenames and capitalization must match the HTML paths exactly.

3. Complete HTML Code — index.html
Copy this code into your index.html file.


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio - Image Gallery</title>
</head>
<body>
    <header>
        <h1>My Personal Portfolio</h1>
        <p>Welcome to my portfolio! Here are some pictures
           related to me, my interests, and my skills.</p>
    </header>

    <main>
        <section>
            <h2>My Images</h2>

            <figure>
                <img
                    src="images/profile.jpg"
                    alt="Portrait photograph of me for my personal portfolio"
                    width="300"
                    height="200"
                >
                <figcaption>My Profile</figcaption>
            </figure>

            <figure>
                <img
                    src="images/coding.jpg"
                    alt="A person writing computer code on a laptop"
                    width="300"
                    height="200"
                >
                <figcaption>My Interest in Coding</figcaption>
            </figure>

            <figure>
                <img
                    src="images/hobby.jpg"
                    alt="A person enjoying a favorite hobby in their free time"
                    width="300"
                    height="200"
                >
                <figcaption>My Hobbies</figcaption>
            </figure>
        </section>

        <section>
            <h2>About My Portfolio</h2>
            <p>
                This portfolio demonstrates how to add images to an
                HTML webpage using the img element. Each image has
                a source path, meaningful alternative text, and
                specified dimensions.
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 My Personal Portfolio</p>
    </footer>
</body>
</html>
4. Example Image Gallery
Here is an illustrative preview of the three types of images to include in your portfolio.

Jett Palmer
1. Profile image

File: profile.jpg

Building Apps: A Beginner’s Guide to App Development
2. Coding image

File: coding.jpg

Outliers: The Story of Success, By Malcolm Gladwell [A Book Report] | by Dominic Timothy | Medium
3. Hobby image

File: hobby.jpg

These are visual references. Download or select three actual image files, save them in your project's images folder, and use the exact filenames shown in the code.

5. Explanation of the <img> Tag
Attribute

Purpose

Example

src

Specifies the image file path.

images/profile.jpg

alt

Describes the image for screen readers and when the image cannot load.

Portrait photograph of me

width

Sets the displayed width in pixels.

300

height

Sets the displayed height in pixels.

200

The <figure> element groups each image with its caption, while <figcaption> provides a visible description.

6. How to Run and Test the Project
Create a folder named Assignment-3.2.

Inside it, create index.html and an images folder.

Place three image files in the images folder.

Ensure the image filenames match the src attributes in your HTML.

Open index.html in your web browser.

Verify that all three images display correctly.

If an image is missing, check the folder name, filename, file extension, and capitalization.

7. Result
A personal portfolio webpage was created using HTML image elements. Three images were added with correct relative paths, meaningful alternative text, and specified width and height attributes. The images can be verified by opening the webpage in a browser.

8. Submission Checklist

index.html — completed portfolio page.

images/profile.jpg — profile image.

images/coding.jpg — coding image.

images/hobby.jpg — hobby image.

Verify that all images load in the browser.

Ensure every image has meaningful alt text.
Important: Submit the actual images folder along with index.html. The HTML file alone will not include the image files, so the images may not display on another computer.



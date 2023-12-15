# Web-dev-assignmen1
<!DOCTYPE html>
<html >

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Dev Course IITK</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #3498db;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

       
        input, textarea {
            margin-bottom: 10px;
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
            width: 100%;
            box-sizing: border-box;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            margin-bottom: 10px;
        } 

    </style>
</head>
<body>

    <header>
        <h1>KNOW THE PERSON-Satvik Pratap Singh</h1>
        <p>Hi!This is my web page ,where I have shared some information about my life.I would love to hear your opinions and suggestions.</p>
    </header>

    <section>
        <h2>About Me</h2>
        <p>My Name is Satvik Pratap Singh.I am second year undergraduate from Chemical Engineering department,IIT Kanpur.</p>
        <p>I have done my Schooling from Kendriya Vidyalaya.</p>
        <p>My Hobbies are Quizzing,Playing Football and Badminton and star gazing.</p>
        <p>I would be glad to interact with you all.You can contact me by mailing me.</p>
    </section>

    <section>
        <h2>Contact Me</h2>
        <p>email id:satvikp22@iitk.ac.in</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message to Satvik:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <input type="submit" value="Submit">
        </form>
    </section>

    <section>
        <h2>Image Gallery</h2>
        <div>
            <img src="image1.jpg" alt="Caption 1">
            <p><a href="source1.html" target="_blank">Source</a></p>
        </div>
        <!-- Repeat the above div structure for additional images -->
    </section>

    <section>
        <h2>Course Timetable of My Third Semester in IITK</h2>
        <table>
            <thead>
                <tr>
                    <th>Day</th>
                    <th>(8:00Am to 8:50Am)</th>
                    <th>(9:00Am to 9:50Am)</th>
                    <th>(10:00Am to 10:50Am)</th>
                    <th>(11:00Am to 11:50Am)</th>
                    <th>(12:00Am to 12:50Am)</th>
                    <th>(6:00pm to 6:50pm)</th>
                    
                    
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Monday</td>
                   
                    <td>ESC 201</td>
                    <th>N/A</th>
                    <th>ESO201</th>
                    <th>ESO204</th>
                    <th>CHE251</th>
                    <th>PHI161</th>

                </tr>
                <tr>
                    <td>Tuesday</td>
                   
                    <td>N/A</td>
                    <th>N/A</th>
                    <th>CHE201</th>
                    <th>N/A</th>
                    <th>N/A</th>
                    <th>N/A</th>

                </tr>
                <tr>
                    <td>Wednesday</td>
                   
                    <td>ESC 201</td>
                    <th>N/A</th>
                    <th>ESO201</th>
                    <th>ESO204</th>
                    <th>CHE251</th>
                    <th>PHI161</th>

                </tr>
                <tr>
                    <td>Thursday</td>
                   
                    <td>ESC 201</td>
                    <th>N/A</th>
                    <th>ESO201</th>
                    <th>ESO204</th>
                    <th>N/A</th>
                    <th>PHI161</th>

                </tr>
                <tr>
                    <td>Friday</td>
                   
                    <td>ESC 201</td>
                    <th>N/A</th>
                    <th>ESO201</th>
                    <th>ESO204</th>
                    <th>CHE251</th>
                    <th>PHI161</th>

                </tr>
               
</tbody>

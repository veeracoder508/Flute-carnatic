<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple HTML Page</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 20px;
            background-color: #f0f0f0; /* Light gray background */
        }
        h1 {
            color: #333; /* Dark gray heading */
        }
        p {
            line-height: 1.6; /* Improved readability */
        }
        .highlight {
            background-color: yellow; /* Highlighted text */
            padding: 2px 5px;
        }
        img {
          max-width: 300px; /* Make image responsive */
          height: auto;
          display: block; /* Prevents image from affecting text flow */
          margin: 20px auto; /* Centers the image */
        }
        ul {
          list-style-type: square; /* Change bullet style */
        }

    </style>
</head>
<body>

    <h1>Welcome to My Webpage</h1>

    <p>This is a simple HTML page demonstrating some basic elements.  We can add text, images, and other content here.  This sentence contains a <span class="highlight">highlighted</span> word.</p>

    <img src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" alt="Google Logo">  <h2>A List of Items</h2>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>

    <h2>A Simple Table</h2>
    <table>
      <thead>
        <tr>
          <th>Header 1</th>
          <th>Header 2</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Row 1, Cell 1</td>
          <td>Row 1, Cell 2</td>
        </tr>
        <tr>
          <td>Row 2, Cell 1</td>
          <td>Row 2, Cell 2</td>
        </tr>
      </tbody>
    </table>

    <p>You can add more content as needed.  Have fun exploring HTML!</p>

</body>
</html>

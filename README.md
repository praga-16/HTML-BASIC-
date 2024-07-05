# HTML-BASIC-
## Ex-1
### Creating a html file to display the contents as seen in the following image.
#### Program:
name : pragatheesvarana AB
<br> roll no : 212221240039

##### table.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Day</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: yellow;
        }
        .main-content {
            width: 70%;
            vertical-align: top;
        }
        .images-content {
            width: 30%;
            vertical-align: top;
        }
        .centered {
            text-align: center;
        }
        .image-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }
        .image-grid img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <table class="center">
        <tr>
            <th colspan="2" class="centered">My Day</th>
        </tr>
        <tr>
            <td class="main-content">
                <ol>
                    <li>wake up early
                        <ul>
                            <li>5AM</li>
                            <li>walk</li>
                            <li>jog</li>
                        </ul>
                    </li>
                    <hr>
                    <li>breakfast
                        <ul>
                            <li>8AM</li>
                            <li>eggs</li>
                            <li>coffee</li>
                        </ul>
                    </li>
                    <hr>
                    <li>go to Saveetha
                        <ul>
                            <li>8AM</li>
                            <li>attend classes</li>
                            <li>to be continued</li>
                        </ul>
                    </li>
                    <hr>
                </ol>
            </td>
            <td class="images-content">
                <table>
                    <tr>
                        <th class="centered">Things to watch</th>
                    </tr>
                    <tr>
                        <td>
                            <div class="image-grid">
                                <img src="c:\Users\PRAGA\OneDrive\Desktop\web table\im1.jpeg" alt="Walking Image">
                                <img src="c:\Users\PRAGA\OneDrive\Desktop\web table\im2.png" alt="Eggs Image">
                                <img src="c:\Users\PRAGA\OneDrive\Desktop\web table\im3.jpeg" alt="Coffee Image">
                                <img src="c:\Users\PRAGA\OneDrive\Desktop\web table\im4.jpeg" alt="Classroom Image">
                            </div>
                        </td>
                    </tr>
                </table>
            </td>
        </tr>
    </table>
</body>
</html>

```
#### Output:
![web table](https://github.com/praga-16/HTML-BASIC-/assets/95266924/e8de7309-71d9-4197-a2ec-8d49bcb2e604)

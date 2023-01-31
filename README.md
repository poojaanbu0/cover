# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a new Django project and app.

### Step 2:
Create a static file directory and mention the changes in settings.

### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

### Step 4:
Write down the code for book cover using HTML and CSS.

### Step 5:
Add images and other contents using CSS record a screenshot of it.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back1.png);
            background-size: cover;
        }
            

        .insight{
            color:yellow;
   }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:red;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 290px;
            width: 110px;
            height: 100px;
            background-size: cover;
        }
     </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(219, 26, 26);">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
               Develop future-proof responsive websites using the latest HTML5 and CSS Technique
            </div>
            <div class="mypic">
                <img src="/static/images/my.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color:rgb(199, 33, 61);">
            </div>
            <div class="author">
               <p><b>POOJA</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Fifthth Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
![](WhatsApp%20Image%202023-01-31%20at%201.05.38%20AM%20(1).jpeg)

## Result:
Thus a website to display the cover page design of a book was successfully created.
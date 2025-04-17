# 9.6
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Comment Form</title>
    <style>
        form {
            min-width: 400px;
        }
        label {
            width: 150px;
            display: inline-block;
        }
        #mySubmit {
            margin-left: 160px;
        }
    </style>
</head>
<body>
    <form method="post" action="http://webdevbasics.net/scripts/demo.php">
        <h1>Send Us Your Comments</h1>
        <p>Required fields are marked with an asterisk *.</p>

        <div class="form-group">
            <label for="myName">*Name:</label>
            <input type="text" name="myName" id="myName" placeholder="your first and last name" required>
        </div>

        <div class="form-group">
            <label for="myEmail">*E-mail:</label>
            <input type="email" name="myEmail" id="myEmail" placeholder="your@domain.com" required>
        </div>

        <div class="form-group">
            <label for="myRating">Rating (1 - 10):</label>
            <input type="range" name="myRating" id="myRating" min="1" max="10">
        </div>

        <div class="form-group">
            <label for="myComments">*Comments:</label>
            <textarea name="myComments" id="myComments" rows="2" cols="20" placeholder="Enter your comments here..." required></textarea>
        </div>

        <div class="form-group">
            <input type="submit" value="Submit" id="mySubmit">
        </div>
    </form>
</body>
</html>

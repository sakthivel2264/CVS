#CVS
<!DOCTYPE html>
<html lang="en">
    <header>
        Certificate Verfication System
    </header>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Certificate Uploader</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="container">
    <div class="form-group">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required>
    </div>
    <div class="form-group">
        <label for="Gmail">Gmail:</label>
        <input type="Gmail" id="Gmail" name="Gmail" required>
    </div>
</div>
    <div class="container">
        <h1>Upload Your Certificate</h1>
        <form action="upload.php" method="post" enctype="multipart/form-data">
            <input type="file" name="certificate" id="certificate" accept=".pdf, .doc, .docx">
            <br><br>
            <input type="submit" value="Upload Certificate">
        </form>
    </div>
</body>
<footer>
      &copy; 2023 CVS  | All rights reserved
</footer>
</html>


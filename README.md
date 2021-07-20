<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment 1</title>
</head>
<body>
    <h1>My Bio Data</h1>
    <form>
        <fieldset> 
            <legend>Personal Information</legend>
            <br>
            <label for="fanme">FirstName:</label> <input type="text" id="fname" name="fname" placeholder="First Name">
            <label for="lanme">LastName:</label> <input type="text" id="lname" name="lname" placeholder="Last Name">
            <br><br>
            <label for="male">Male</label><input type="radio" id="male" name="gender">
            <label for="female">Female</label><input type="radio" id="female" name="gender">
            <label for="other">Other</label><input type="radio" id="other" name="gender">
            <br><br>
            <label for="dob">Date of Birth:</label> <input type="date" id="dob" name="dob">
            <br><br>
            <label for="email">E-Mail:</label> <input type="email" id="email" name="email" placeholder="Enter your Email">
            <br><br>
            <label for="pno">Phone</label> <input type="number" id="pno" name="pno" placeholder="+91" maxlength="10">
            <br><br>
            <label for="height">Height</label> <input type="number" id="height" name="height" placeholder="Enter your height in feet">
            <br><br>
        </fieldset>

        <fieldset>
            <legend>Education</legend>
            <br>
            <label for="school">School Name:</label> <input type="text" id="school" name="school" placeholder="School Name">
            <br><br>
            <label for="class">Class:</label> <input type="number" id="class" name="class" placeholder="Enter Class">
            <br><br>
            <label for="stream">Stream:</label>  
            <input list="stream" name="stream" placeholder="Stream">
             <datalist id="stream">
              <option value="PCM">
              <option value="Commerce">
              <option value="Arts">
              <option value="Music">
              <option value="Games">
             </datalist>
             <br><br>
             Marksheet: <button type="menu">Choose File</button> No File Chosen
        </fieldset><br>
         <button type="submit">Submit</button>
    </form>
</body>
</html>

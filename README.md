<!DOCTYPE html>
<html>
<head>
    <title>Registration Form</title>
</head>
<body>

    <h2>Registration Form</h2>

    <form>

        <label>Name:</label>
        <input type="text" name="name">
        <br><br>

        <label>Email:</label>
        <input type="email" name="email">
        <br><br>

        <label>Password:</label>
        <input type="password" name="password">
        <br><br>

        <label>Gender:</label>
        <input type="radio" name="gender" value="male"> Male
        <input type="radio" name="gender" value="female"> Female
        <br><br>

        <label>Date of Birth:</label>
        <input type="date" name="dob">
        <br><br>

        <label>Course:</label>
        <select name="course">
            <option>B.Sc Computer Science</option>
            <option>BCA</option>
            <option>B.Sc IT</option>
            <option>B.Com</option>
        </select>
        <br><br>

        <input type="submit" value="Submit">

    </form>

</body>
</html>

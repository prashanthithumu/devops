<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Event Registration Form</title>
</head>
<body>
    <h2>Event Registration Form</h2>
    <form action="/submit_registration" method="POST">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br><br>
         <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone" required><br><br>
        
        <label for="event">Select Event:</label>
        <select id="event" name="event" required>
            <option value="event1">Event 1</option>
            <option value="event2">Event 2</option>
            <option value="event3">Event 3</option>
        </select><br><br>
        
        <input type="submit" value="Register">
    </form>
</body>
</html>

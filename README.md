

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Survey Form Lab</title>
</head>
<body>

  <h1 id="title">Developer Survey</h1>
  <p id="description">We want to know more about your coding preferences and experience.</p>

  <form id="survey-form">
    <!-- Name -->
    <label id="name-label" for="name">Name:</label>
    <input id="name" type="text" placeholder="Enter your name" required>

    <!-- Email -->
    <label id="email-label" for="email">Email:</label>
    <input id="email" type="email" placeholder="Enter your email" required>

    <!-- Number -->
    <label id="number-label" for="number">Age:</label>
    <input id="number" type="number" placeholder="Enter your age" min="10" max="99" required>

    <!-- Dropdown -->
    <label for="dropdown">Favorite Language:</label>
    <select id="dropdown" required>
      <option value="">Select one</option>
      <option value="javascript">JavaScript</option>
      <option value="python">Python</option>
    </select>

    <!-- Radio buttons -->
    <label>Preferred Development Environment:</label>
    <input type="radio" name="environment" value="web" required> Web
    <input type="radio" name="environment" value="mobile"> Mobile

    <!-- Checkboxes -->
    <label>Technologies You Use:</label>
    <input type="checkbox" name="tech" value="html"> HTML
    <input type="checkbox" name="tech" value="css"> CSS

    <!-- Textarea -->
    <label for="comments">Additional Comments:</label>
    <textarea id="comments" placeholder="Your comments"></textarea>

    <!-- Submit button -->
    <button id="submit" type="submit">Submit</button>
  </form>

</body>
</html>



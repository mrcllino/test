<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<html>
<body>

<h1>The autocomplete attribute</h1>

<p>The autocomplete attribute specifies whether or not an input field should have autocomplete enabled.</p>

<p>Fill in and submit the form, then reload the page to see how autocomplete works.</p>

<p>Notice that autocomplete is "on" for the form, but "off" for the e-mail field!</p>

<form action="/action_page.php" autocomplete="on">
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" autocomplete="off"><br><br>
  <input type="submit" value="Submit">
</form>

</body>
</html>

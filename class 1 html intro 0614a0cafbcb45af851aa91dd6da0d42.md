# class 1 html intro

heading (h1-h5)

```html
<h1> heading 1</h1>
<h2> heading 2</h2>
<h3>heading 3</h3>
```

List in html

```html
<ol>cat</ol>
    <li>cat</li>
    <li>fox</li>
    <li>dog</li>
  
```
```

**File Path**

```html

```

| Path | Description |
| --- | --- |
| <img src="picture.jpg"> | The "picture.jpg" file is located in the same folder as the current page |
| <img src="images/picture.jpg"> | The "picture.jpg" file is located in the images folder in the current folder |
| <img src="/images/picture.jpg"> | The "picture.jpg" file is located in the images folder at the root of the current web |
| <img src="../picture.jpg"> | The "picture.jpg" file is located in the folder one level up from the current folder |

**HTML Paragraphs**

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

**HTML Line Breaks**

```html
<p>This is<br>a paragraph<br>with line breaks.</p>
```

**The Poem Problem**

```html
<p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>
```

**image mapping**

[https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15762.051347316128!2d38.77843275000002!3d9.016893550000004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b859e260e7aa5%3A0xc3f851c8a4166767!2sKazanchis%2C%20Addis%20Ababa%2C%20Ethiopia!5e0!3m2!1sen!2ses!4v1700292486836!5m2!1sen!2ses](https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15762.051347316128!2d38.77843275000002!3d9.016893550000004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b859e260e7aa5%3A0xc3f851c8a4166767!2sKazanchis%2C%20Addis%20Ababa%2C%20Ethiopia!5e0!3m2!1sen!2ses!4v1700292486836!5m2!1sen!2ses)

<iframe src="[https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15762.051347316128!2d38.77843275000002!3d9.016893550000004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b859e260e7aa5%3A0xc3f851c8a4166767!2sKazanchis%2C Addis Ababa%2C Ethiopia!5e0!3m2!1sen!2ses!4v1700292486836!5m2!1sen!2ses](https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15762.051347316128!2d38.77843275000002!3d9.016893550000004!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x164b859e260e7aa5%3A0xc3f851c8a4166767!2sKazanchis%2C%20Addis%20Ababa%2C%20Ethiopia!5e0!3m2!1sen!2ses!4v1700292486836!5m2!1sen!2ses)" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

**The <form> Element**

```html
<form>
.
form elements
.
</form>
```

**The <input> Element**

```html
Type	Description
<input type="text">	Displays a single-line text input field
<input type="radio">	Displays a radio button (for selecting one of many choices)
<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
<input type="submit">	Displays a submit button (for submitting the form)
<input type="button">	Displays a clickable button
```

**Text Fields**

```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```

**Radio Buttons**

```html
<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>
```

**Checkboxes**

```html
<form>
  <input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
  <label for="vehicle1"> I have a bike</label><br>
  <input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
  <label for="vehicle2"> I have a car</label><br>
  <input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
  <label for="vehicle3"> I have a boat</label>
</form>
```

**The Submit Button**

```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
```
# Standard Template

[Website](https://michaelbarney.github.io/LinkFree/Templates/Standard/)

<img src="https://imgur.com/a/3LqwkPR" alt="Victor profile picture" width="250px">

## How to Use
### index.html
 1. **Title**
    This is the name that is given to the page.
	   ```
	   <title>Victor's Linktree</title>
	   ```
 2. **(Optional) Favicon** 
	To change the favicon, just replace the "favicon.ico" file. You can generate the .ico file in a website like [favicon.io](https://favicon.io/).
 3. **Image**
	 This is the user image that is shown. Make sure it is square and substitute the "src" property with its url. You can generate the url in a website like [imgur](https://imgur.com/).
	```
	<img  id="userPhoto"  src="https://imgur.com/a/3LqwkPR"  alt="User Photo">
	```
 4. **Username**
	Your Instagram username. Change the "href" property with its url and add substitute the text with your @.
	```
	<a  href="https://www.instagram.com/victorsyin"  id="userName"></h3>@victorsyin</a>
	```
 5. **Links**
 To add your clickable links just substitute, delete or copy the "a" tags inside the "links" div with your desired hyperlinks.
	```
	<div  id="links">

		<a  href="https://victorsyin.medium.com"  target="_blank">Medium</a>

		<a  href="https://m.me/victorsyin"  target="_blank">FB Messenger</a>
		
		<a  href="https://cal.com/victorsyin/meet"  target="_blank">Meet with me</a>

	</div>
	```
### style.css
 6. **Colors**
	 Substitute the background and accent colors with your desired pallete.
	 ```
	 --bgColor: white;
	--accentColor: #39e09b;
	 ```
 7. **Fonts**
	 You can import the font from a website like [Google Fonts](https://fonts.google.com/) and substitute the "--font" variable with its implementation.
	 ```
	 @import  url('https://fonts.googleapis.com/css?family=Karla:400,700&display=swap');
	 
	 --font: 'Karla', sans-serif;
	 ```

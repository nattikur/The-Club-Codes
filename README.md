Hello there! Thanks for downloading this theme. I'm going to run through the installation of the theme here & explain in detail how you can make the most of all the features I have added in for you.<p>

1. INSTALLING THE THEME
<ul>
<li>Go onto your blog and click "Edit Theme".
<li>Click "Edit HTML".
<li>Find the file called "MAIN HTML" in this folder.
<li>Remove everything in your tumblr's HTML and copy and paste the notepad document in there instead.
<li>Click "Update Preview" at the top & then click "Save".
<li>Press the arrow at the top to go back to the main blog options view.
<li>Scroll down and go through each option. Make sure everything looks how you like.
</ul><p>

2. ADDING THE PAGES

<U>2.1 Info Page</u>
<ul>
<li>At the bottom of your theme options, select "+ Add a page".
<li>You need to select "Custom Layout".
<li>Make sure the url is /info (or whatever you want the page name to be).
<li>Go into the "Pages" folder that you downloaded and open the "Info" notepad file. Copy and paste everything in there into the custom HTML of your page.
<li>Note: Unfortunately, all of those options you've changed to make your theme look as you want it WILL NOT COME OVER TO THIS PAGE. You will have to manually input all the styling information yourself. Now, I've made this as easy as possible by annotating the styling. There are only several things that you need to have to hand:
<ul>
		<li>background color
		<li>background image
		<li>font color
		<li>font family
		<li>accent color
		<li>headers color
		<li>content color
</ul>
Just go through the style information and everywhere where you see one of those annotations, make sure it matches what's on your current skin. The format should be quite easy to recognise.
<li>Directly underneath the styling it will say "<!-- TOP STARTS -->". Here you will need to manually imput the Title of your blog and the subtitle.
<li>Underneath the top HTML is the sidebar HTML. The first thing in the sidebar that you need to edit are the "info buttons". This is the HTML for the small little white buttons in the sidebar with short clippets of information. I've put in some examples for now, but really, they can be anything you like.<br>
Each information button appears in the html as such:<br>
		<textarea><div class="aboutbut">WORDS</div></textarea><bR>
Input whatever information you like in there, but try to keep it short. You can have as many or as few of these as you like, but just a quick note: it's looks better when you have a multiple of 2.<br>
Once you've finished this, press "Update Preview" and "Save" again.
<li>Right underneath the Info Buttons are the Updates. Unfortunately, these will not be automatically pulled off of your homepage, so you will have to input them manually.<br>
If you would rather not have to do this, feel free to remove the updates from this page by deleting everything starting from "<!-- updates start -->" to "<!-- updates end -->"<br>
Editing the updates should be quite self explanitory. In between the <textarea><b></textarea> tags, put the date of your update in this format: "##/##/####". Then, where it says "Update 1", put the content of your update.<br>
I have also explained in the HTML how to add additional updates.<br>
Please note, the updates should show with the most recent at the top.<br>
Once you have finished this, press "Update Preview" and then "Save".
<li>Underneath updates, you'll find the basic information box. The only thing you need to edit in here is the "Established" date which should be right at the top. Find the part where it says "##/##/####" and replace that with the date that the website was launched.
<li>Now it's time to start on the actual page content. Find "<!-- page begins -->". Inside <textarea><h1></textarea> tags, make sure the title is right (I have used "Information" but you can change this).<br>
Next, it's time to imput your content. I have put in several paragraphs of "Ipsum" text, which is just randomly generated mummble jumble, to show you how it will look. Please remove all this and imput your information yourself. Remember to use HTML - so you must follow the following styling:<br>
<ul>
		<li>BOLD: <textarea><b>bold</b></textarea>
		<li>ITALIC: <textarea><b>italic</i></textarea>
		<li>UNDERLINE: <textarea><u>underline</u></textarea>
		<li>LINK: <textarea><a href="www.link.com">link name</a></textarea>
		<li>NEW LINE: <textarea><br></textarea>
		<li>NEW PARAGRAPH: <textarea><br><br></textarea>
</ul>
Once you have done that, press "Update Preview" and "Save" and your page should be done!
</ul><p>


<u>2.2 Tags Page</u>
<ul>
<li>At the bottom of your theme options, select "+ Add a page".
<li>You need to select "Custom Layout".
<li>Make sure the url is /tags (or whatever you want the page name to be).
<li>Go into the "Pages" folder that you downloaded and open the "Tags" notepad file. Copy and paste everything in there into the custom HTML of your page.
<li>Note: Unfortunately, all of those options you've changed to make your theme look as you want it WILL NOT COME OVER TO THIS PAGE. You will have to manually input all the styling information yourself. Now, I've made this as easy as possible by annotating the styling. There are only several things that you need to have to hand:
<ul>
		<li>background color
		<li>background image
		<li>font color
		<li>font family
		<li>accent color
		<li>headers color
		<li>content color
</ul>
Just go through the style information and everywhere where you see one of those annotations, make sure it matches what's on your current skin. The format should be quite easy to recognise.
<li>Directly underneath the styling it will say "<!-- TOP STARTS -->". Here you will need to manually imput the Title of your blog and the subtitle.
<li>Then you have your page. On each line is a new "tag". For each "tag" there are two things you need to edit:
<ul>
  <li>THE LINK : find the bit that says "/tagged/tag" and replace the word "tag" with whatever the tag is. NOTE: if the tag has spaces in, e.g. "doctor who", then you will need to write "doctor-who".
  <li>THE NAME: where it says "#tag", replace the word #tag with the name of the tag, for instance "doctor who". Do not remove the #.
You can have as many or as few of these as you want, however they look best in multiples of four.
</ul>
Once you have done that, press "Update Preview" and "Save" and your page should be done!
</ul><p>


<u>2.3 Staff Page</u>
<ul>
<li>At the bottom of your theme options, select "+ Add a page".
<li>You need to select "Custom Layout".
<li>Make sure the url is /staff (or whatever you want the page name to be).
<li>Go into the "Pages" folder that you downloaded and open the "Staff" notepad file. Copy and paste everything in there into the custom HTML of your page.
<li>Note: Unfortunately, all of those options you've changed to make your theme look as you want it WILL NOT COME OVER TO THIS PAGE. You will have to manually input all the styling information yourself. Now, I've made this as easy as possible by annotating the styling. There are only several things that you need to have to hand:
<ul>
		<li>background color
		<li>background image
		<li>font color
		<li>font family
		<li>accent color
		<li>headers color
</ul>
Just go through the style information and everywhere where you see one of those annotations, make sure it matches what's on your current skin. The format should be quite easy to recognise.
<li>Directly underneath the styling it will say "<!-- TOP STARTS -->". Here you will need to manually imput the Title of your blog and the subtitle.
<li>Then you have your page. Seperated by line breaks, I have put in four staff members originally, but you can have as many or as few as you like. For each staff member, you will be using this template:<br>
		<textarea>"<a href="http://BLOGTITLE.tumblr.com" title="BLOGTITLE"><div class="staff" style="background-image: url(IMG);"></div></a>"</textarea><br>
You will need to first of all get the staff member's blog title and paste that into the two places where it says "BLOGTITLE". Then, to get their icon: go onto their blog, right click, click "View Page Source", search for <textarea>'<link rel="shortcut icon"'</textarea> and copy the img url next to it. Paste that where it says "IMG" in the template.<
<li>Do the same for each staff member.
<li>Once you have done that, press "Update Preview" and "Save" and your page should be done!
</ul><p>

<u>2.4 Gallery Page</u>
<ul>
<li>At the bottom of your theme options, select "+ Add a page".
<li>You need to select "Custom Layout".
<li>Make sure the url is /gallery (or whatever you want the page name to be).
<li>Go into the "Pages" folder that you downloaded and open the "Gallery" notepad file. Copy and paste everything in there into the custom HTML of your page.
<li>Note: Unfortunately, all of those options you've changed to make your theme look as you want it WILL NOT COME OVER TO THIS PAGE. You will have to manually input all the styling information yourself. Now, I've made this as easy as possible by annotating the styling. There are only several things that you need to have to hand:
<ul>
		<li>background color
		<li>background image
		<li>font color
		<li>font family
		<li>accent color
		<li>headers color
</ul>
Just go through the style information and everywhere where you see one of those annotations, make sure it matches what's on your current skin. The format should be quite easy to recognise.
<li>Directly underneath the styling it will say "<!-- TOP STARTS -->". Here you will need to manually imput the Title of your blog and the subtitle.
<li>Then you have your page. On each line is a new image. To add an image, simply use this format: <textarea>'<img src="IMGURL">'</textarea><br>
You can have as many or as few of these as you want.<br>
Once you have done that, press "Update Preview" and "Save" and your page should be done!
</ul><p>



THANK YOU SO MUCH! This is your guide over.<bR>
There are a few more components you can play around with, but I have tried my best to detail them within the HTML. So keep an eye out!<br><br>

Thanks!!

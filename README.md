How To Add Pop Up Light Box Video Player In Blogger ?

Step 1: Go to blogger and login to your account.

Step 2: Open Layout of your blog.

Step 3: Click on Add a gadget and choose HTML/JAVASCRIPT.

Step 4: Copy code given below and paste it in to HTML/JAVASCRIPT window.

For YouTube Videos: 
<link rel="stylesheet" type="text/css" href="https://rawgit.com/fahimraza/FK/master/vplayer.css" />
<div id="jquery-script-menu">
<a rel="nofollow" href="Javascript:" class="link-lightbox" data-videoid="YOUR VIDEO ID" data-videosite="youtube"><img src="https://i.ytimg.com/vi/0mFXo88pyaU/hqdefault.jpg"/></a><br />
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script type="text/javascript" src="https://rawgit.com/fahimraza/FK/master/vplayer.js"></script></div>

For Vimeo Videos: 
<link rel="stylesheet" type="text/css" href="https://rawgit.com/fahimraza/FK/master/vplayer.css" />
<div id="jquery-script-menu">
<a rel="nofollow" href="Javascript:" class="link-lightbox" data-videoid="YOUR VIDEO ID" data-videosite="vimeo"><img src="https://i.ytimg.com/vi/0mFXo88pyaU/hqdefault.jpg"/></a><br />
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script type="text/javascript" src="https://rawgit.com/fahimraza/FK/master/vplayer.js"></script></div>


Step 5: Replace "YOUR VIDEO ID" with ID of video which you want to play in pop up.

How To Get ID Of A Youtube Video ?

Open a YouTube video and get the final elements from its URL like below is the URL of a video and the highlighted part of the link after "v=" is its ID

https://www.youtube.com/watch?v=0mFXo88pyaU

0mFXo88pyaU is the ID of this video.

How To Get ID Of A Vimeo Video ?

Similar to YouTube video ID, Vimeo also have video ID in its URL, Like this:

https://vimeo.com/188471047

188471047 is ID of this video.

Step 6: Save your gadget and you are done.

How To Customize Video Player ?

You can show your video's thumbnail which when clicked will show the pop up or you can show some text like "watch this amazing video" both of these will play role of a trigger.

To add your video's thumbnail replace https://i.ytimg.com/vi/0mFXo88pyaU/hqdefault.jpg with your video's thumbnail link.

To show text Replace this piece of code with your text:

<img src="https://i.ytimg.com/vi/0mFXo88pyaU/hqdefault.jpg"/>

Replace YOUR VIDEO ID with your video ID.

I hope you loved this post, if not and you want to give any suggestion, feel free to contact us or leave a comment below. Your feedback is really valuable!

Thanks for visiting 101Helper. ♡ Happy Blogging!

Search Keywords: Jquery on-click pop up light box video player for blogger, Popup video player, pop up youtube video player, pop up vimeo video player, how to create a video player with jquery, jQuery YouTube Popup Player Plugin

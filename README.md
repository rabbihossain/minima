#Welcome

Welcome to the documentation of Minima Theme. Here is the Theme Information.

Theme Name : Minima - Minimalistic Theme For Ghost

Author : Rabbi Hossain

Created : 20 Dec 2013

Version : 1.0
File structure & Information

This Ghost theme is powered by Gumby framework. So, it contains all the files of Gumby Framework. This also includes the “.hbs” files needed for the theme.

After Unzipping the Themes .zip file, You will see a folder named “Minima”. This folder contains Three .hbs & a assets folder. Here the the file structure -

1. assets (this folder contains the contains the css, javascipt & fonts
    folder need for the theme to work)

* css (contains the CSS stylesheet files)

* js (Contains the Javascript Files)

* fonts (fonts files are stored here)

2. default.hbs (This file contains codes of header, footer & sites meta information.)

3. index.hbs (Contains sites home page codes)

4. post.hbs (Contains the code for post display page)

OK, Let’s finish this & go to next procedure.

#Pre-Installation Procedure

Ghost Blogging Platform doesn’t provides any API or hook to integrate some theme options to theme. SO, we need to do it manually.

In this theme, I have added some social buttons. In this process we are going to configure them before installing the theme.

To do it, open the index.hbs file with a code editor. Now, search for these following lines. You will be able to find them on line number 29 to 32.

    <!-- Facebook --><div class="primary btn"><a href="#" target="_blank"><i class="icon-facebook"></i></a></div>

    <!-- Twitter --><div class="primary btn"><a href="#" target="_blank"><i class="icon-twitter"></i></a></div>

    <!-- Linked In --><div class="primary btn"><a href="#" target="_blank"><i class="icon-linkedin"></i></a></div>

    <!-- Google Plus --><div class="primary btn"><a href="#" target="_blank"><i class="icon-gplus"></i></a></div>

These four lines of codes contains the social link, you want to share on your ghost blog. To add your social profile link. Just change the “#” after the `<a href=` code. That means if you want to add your Facebook profile link. Just change the code for Facebook like this,

    <!-- Facebook --><div class="primary btn"><a href="Your Facebook Profile Link Here" target="_blank"><i class="icon-facebook"></i></a></div>

Suppose, you don’t have a Linked In profile and you don’t want to show the Linked In button on your site. To do is, just delete the line for Linked In and It will not appear anymore.

#Installing The Theme

After configuring the pre-installation procedure, open the main directory of your Ghost blog. Then go to /contents/themes/ directory. Now, upload the theme folder named “Minima” into this directory.

Now restart Ghost. After restarting, go to the ghost administration panel and then navigate to Settings > General . On theme section, select Minina from the drop-down menu. And click Save button to save your settings.

OK, you have successfully installed the theme.

#Blog Setup

Go to your ghost administration panel and then navigate to Settings > General . You will get some settings there. I am describing them here

* Blog Title: Changes your Blog’s title.

* Blog Description: Changes your Blog’s description.

* Blog Logo: Upload a Logo for your blog in either ‘.png’, ‘.jpg’ or ‘.gif’. Blog Cover: Upload your blog cover image in either ‘.png’, ‘.jpg’ or ‘.gif’.

* Email Address: This is the email admin notifications are sent too. It must be a valid email.

* Posts per page: This is how many posts are displayed per page. This should be a numeric value.

* Theme: This will list all the themes in your content/themes directory. Selecting one from the drop-down will change your blog’s look.

Now, go to Settings > User. You will also get some options here. Here they are,

* Name: Add your name here. They will appear on post page.

* Email: You email will be added here. This is also your login credential

* Location: Changes your location information.

* Website: Add your website link here.

* Bio: Add some of information related to you, here. This will appear on post page.

Click on the User logo beside your name and upload your profile picture in either ‘.png’, ‘.jpg’ or ‘.gif’. This will appear on Post page.

#Extra Post Options

I have added some extra option in this theme. This will help you to add Youtube or Vimeo video on your post. You can even set a Featured image or video for your post. To do this, follow this procedures.

###Adding Youtube Viedo On post

Go to the youtube video and copy the embedding code. Now go to your post editor and add video embed code like this,

    <article class="youtube video" >
    Your embed code will be here
    </article>

Your video will be added to the post

###Adding Vimeo Video On Post

Go to the vimeo video and copy the embedding code. Now go to your post editor and add video embed code like this,

    <article class="vimeo video" >
    Your embed code will be here
    </article>

Your video will be added to the post

###Setting Up Featured Image or Video For Posts

Setting up a featured image or video to your post is easy. Just add your image or video embedding code at the top of your post, when you’re writing. They will be featured automatically.

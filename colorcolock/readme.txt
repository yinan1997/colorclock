April 9, 2020

This work-in-progress contains a commented version of everything we've discussed to date. This is both to provide the JavaScript utilities we need, and to catch everyone up to the where we should be as of today's class.

The aforementioned utilities are:
  • an older version of jQuery for assured compatibility with the color animation plug-in
  • an older color animation plug-in for jQuery that was chosen by popular vote for its very limited programming needs. We can discuss modern alternatives, such as CSS-only color animations, in class if time allows, and vanilla javascript to elminate the use of jQuery entirely, if desired.
  • a function that uses intermediate programming/color theory to change the text color of our clock based on the background color dictated by the time.
We will cover the use of jQuery and the color animation plug-in, but not the core code of any of the above.

Also included are untested example splash screens and icons for the app. As we discussed, these are meant to show the variance in screen sizes for the iOS ecosystem (by unanimous vote, as we have no Android users in the class). If you want to develop this app further, you'll need to confirm image dimensions and filenames for the proper use of these images and icons. You'll need to add additional files to account for dimensions of modern form factors like the X series.

Finally, I've also included the cache manifest and htaccess files we talked about when discussing offline use of the app. As a reminder, by unanimous vote, we won't be discussing support for offline use of a web app due to lack of interest and our limited collective and programming background. Some of you inquired about the deprecated way of doing it, because it still works in most browsers to some degree and requires no code. So I've included an untested example that we can explore if time allows. However, Chrome is scheduled to remove support for this approach this month. We may also discuss the modern version of the offline solution, which uses service workers.

This uses what's called a "cache manifest." Serving a cache manifest requires that your server be setup to know what a manifest is. This is easily accomplished when using an Apache server by using an htaccess file. 

This folder already has an htaccess file in it so, if you know how to use this feature, you can copy the entire folder to a server when you're done with your app. However, as system files are typically invisible, I've duplicated the document as a text file. If you prefer to test this demo (remember, this is an untested example that should serve as a model for you to investigate further), simply upload the text file and then rename it, on the server, from "htaccess.txt" to ".htaccess"  
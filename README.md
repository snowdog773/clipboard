# clipboard

Mobile site is complete to my satisfaction. I have started the desktop version using a separate CSS file, no issues thus far though I could use some guidance
on how to take font sizes out of figma and convert them to CSS, ditto for spacings. Currently I am eyeballing everything and a long way from pixel perfect.

At present, anything from "Access Clipboard Anywhere" and beyond is unstyled. NB to create desktop.css I cut and pasted everything out of mobile.css to give me a starting point, 
therefore all the stylings after "Access Clipboard Anywhere" are remnants of the mobile site and should not be considered completed.

Also I found a cool gizmo to convert hex colour values into CSS filter properties, which I used to apply colour to the hover states of the Facebook, Twitter and Instagram 
links at the end of the page.

https://codepen.io/sosuke/pen/Pjoqqp


-----------------------------------------------------------------------EDIT------------------------------------------------------------------------------

Site has been pretty much rebuilt from the ground up on the latest push. Mobile site has been carefully redesigned to match the design plan as closely as possible. Desktop site has been started but there is still work to do. There is also a point on resizing (around 700px width) where the cta buttons go a bit weird so possibly needs a "tablet" CSS stage to fix that.

QUESTION: I noticed in class you were setting all your font sizes in em units and converting them from the px units given in Figma's inspector. What is the advantage of using em units? and how do you calculate them? Would it be possible to spend a little time in class reviewing the use of em units? I realise they are relative to one another, but when I try and use them I end up breaking more things than I fix.

---------------------------------------------------------------------EDIT---------------------------------------------------------------------------------

FINAL COMMIT 3/12/21

Thanks for the feedback from my last push. I think all issues have now been addressed. The text breaking the ctn buttons bug has been fixed, the paragraph widths have been restricted to the proper sizes, the computer image has been optimised to be nicely responsive across all screen sizes - a 3rd media query has been included here to cater for larger displays. The footer has also been adjusted to flex wrap for tablet sized displays which I think looks quite pleasing, as well as an adjustment for larger displays to restrict the footer width.

I have got all sizes and spacing on the page as close as I am able to the figma plan with the exception of the footer. Although it would be possible to lock the layout down to the nearest pixel, I felt it better to allow flexbox to decide the spacing of the 3 main elements to produce a more pleasing layout across a wider range of display sizes.

# Optimized Bulgarian keyboard layout
An optimized Bulgarian keyboard layout based on Colemak.

![image](https://user-images.githubusercontent.com/6117115/225586110-0bea6537-3451-4616-be57-43a18ede21c5.png)

This is a keyboard layout that I initially posted back in 2014 on the Colemak forums here:
[https://forum.colemak.com/topic/1934-optimizing-colemak-for-bulgarian-cyrillic/](https://forum.colemak.com/topic/1934-optimizing-colemak-for-bulgarian-cyrillic/)

This is a quote from my post there explaining how I optimized the layout:

```
Here is how I approached the problem of fitting all 30 bg letters on a standard us keyboard. 
First, I generated several layouts trying to optimize each of them:
1) based on letter frequency (in Bulgarian; not Russian, English, or another language)
2) by minimizing the amount of disruption to the base Colemak layout
3) using several training text (fiction, non-fiction, wikipedia and newspaper articles) in 
   Bulgarian to do a more detailed analysis using the website: 
   [http://patorjk.com/keyboard-layout-analyzer/#/main](http://patorjk.com/keyboard-layout-analyzer/#/main)  
   (The analysis was a bit of a pain as the website does not accept user-based layouts, so 
   I had to map cyrillic letters in my test layouts to latin letters on existing layouts, and so on, and so on ...)
4) using common sense

I ended up with several more or less equivalent layouts according to the subjective and objective measures above. 
I tested them for a month or so, and ended up with the following "best" layout, which I have been using for 
almost a year now (touch typing of course) without any wrist injuries! ;)
```

Now I've been using that layout for 10 years and decided to share it in case others are interested.

## Installation on Linux

Copy `bg_optim` to  `/usr/share/X11/xkb/symbols/`.

Then copy `evdev.xml` to `/usr/share/X11/xkb/rules/`.

Log out and log in. Layout should be available after that.

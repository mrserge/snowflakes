#Snowflakes

for this holiday season we give you a simple way to annoy your website visitors and waste their CPU cycles - Yes you've guessed it snowflakes on a webpage.

Now we know, this used to be done the old fashion way in the 90ies, but now we have `canvas` and `pointer-events:none`, so the pesky things won't interfere with anything else on the page.

Say thank you to @mrserge for asking me if I can code this useless thing.

Oh, usage:

add a script tag pointing to snowflakes.js, and then in your domready function call `window.snowflakes();`

You can also configure the amount of snow that you want by doing this:

    window.snowflakes({amount:300}); // three hundred snowflakes

Also there is a boolean `nuclearMode` option that will make your visitors leave the website even faster.

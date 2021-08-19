
<p align="center">
    <img style="width: 200px;" src="img/dark-on-light-rgb.png" alt="Viget Logo" />
</p>

---

#### Which Way And Why?

After reading the brief and knowing the time constraint I decided to roll with UI/Interface. I went this route over the application development because I have very little knowledge of using and manipulating JSON data. This said after I was done with the UI/Interface markup I went back and started to teach myself how to parse out the data in the JSON file to HTML and for my own edification, I intend to finish it up over the week.

---

#### Where To Start?

So the first thing I like to do when given the absolute bare bones of a design is, bring it over to Sketch and mark out some pointers. Match the font-sizes, line-heights, letter spacing, and margins as best I can. Nothing to extensive just a cheap and dirty red-line for me to work from. And make a simple SVG arrow for the button. Took ~10minutes.

Next up, set up the files and file structure. Another very fast process. Most weeks I'm checking to see if my "go-to files" are current, for instance, do I have the latest build of JS for safety reasons. After all my files are set up I'll open one of my go-to apps for compiling projects, CodeKit. This is why you'll see everything is written in .kit files. It's a great way to write partials and pull them in without having to use any serverside scripting. I'm just at home using Terminal. After all, is building correctly I get to cutting. My base is to hold everything together for this project is Bootstraps grid, I'm only relying on the grid for the outer container as a fast workaround. Though not typical for projects I usually do I am more than happy and capable of making my own layout. I went Bootstrap over "The Grid" because I'm more confident using it.

---

#### The Conundrum!

So as you rightly need to you need to see that I can use JavaScript. And you do say that both projects have a feature that uses JavaScript. I saw the UI/Interface both needing and not needing JavaScript to work. So I have two versions of this project one with and one without JavaScript the point being to show that the same result can be achieved if someone (I still yet to find anyone that does) turns off JavaScript.

- [Buildout One - No JavaScript](build/index.html)
- [Buildout Two - With JavaScript](build/index-1.html)

---

#### The Small Things...

Replaced the hero .jpg image with a .webp for better file size, 792.3K - 25.3K, a saving of 96.8% and in turn giving a faster load time. All icons are SVGs on the page thus eliminating server requests and again should improve on load times.

A tiny note on the hero image, I passed the image through the built-in compressor inside of CodeKit, this is the only physical change I made to the image. The grayscale effect I'm passing as a class, I've done this because for the last nine years of working I know clients like to have options, simple options. So if they don't have to take an image re-size or desaturate it the happier they are. And if they decide later they do want the image to be full color they just have to remove a class, not get mad at the dev that they didn't save a backup the image when they desaturated it.

---

#### How Much!?

<b>Total Time:</b> 3hours.

---

And this is for your mouse...

       _--"-.
      .-"      "-.
     |""--..      '-.
     |      ""--..   '-.
     |.-. .-".    ""--..".
     |'./  -_'  .-.      |
     |      .-. '.-'   .-'
     '--..  '.'    .-  -.
          ""--..   '_'   :
                ""--..   |
                      ""-'
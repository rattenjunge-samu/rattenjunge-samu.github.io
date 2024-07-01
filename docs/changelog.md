# Changelog

I'll try to track some of the changes done to the site in here.

## 01/07/2024 more styling

Time to wipe off the dust here ...

I noticed the colors of the locally served page differ from the github build.

I can not pinpoint the cause of this problem. However this was solved when I updated the mkdocs material from 9.1.4 to 9.5.27.

However now the contrast of code-blocks and similar elements against the background is too low, so I look into fixing this.

Lowering the brightness of the .md-content background color seems sufficient for now.

## 06/10/2023 mainly styling

I'm trying to customize some features I don't like in the default style.

#### Heading colors

I don't like the default text color for headings in the Material for MkDocs design. It blends in too much with the other text and makes it hard to differentiate.

However going with dark-orange seems a bit too hard? I'll stick with this for now, because it works in the bright theme as well and is a nice contrast to the blueish accent color.

Maybe something gray will fit better.

#### Content-background

By default the background-color of the content (the whole section containing the text) is the same as the site-background. Again I felt it was somewhat confusing with the two tables-of-content left and right.
I chose a slightly brighter color and it's ok for me.

#### Added changelog

Duh

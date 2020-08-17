## Welcome to GitHub Pages

<iframe width="560" height="315"
src="https://www.youtube.com/embed/MUQfKFzIOeU" 
frameborder="0" 
allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen></iframe>


You can use the [editor on GitHub](https://github.com/rodrigohmu/rodrigo.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rodrigohmu/rodrigo.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<figure class="video_container">
<iframe width="100%" height="400" src="https://www.youtube.com/embed/MUQfKFzIOeU" frameborder="0" allowfullscreen="true"></iframe>
<script src="yellow/youtube.external.subtitle.js"></script>
<script src="yellow/subtitles.parser.min.js "></script>
<script>
var loadSRT = function(url, callback) {
    var httpRequest = new XMLHttpRequest();

    httpRequest.onreadystatechange = function() {
        if (httpRequest.readyState === XMLHttpRequest.DONE) {
            var subtitles = parser.fromSrt(httpRequest.responseText, true);

            for (var i in subtitles) {
                subtitles[i] = {
                    start : subtitles[i].startTime / 1000,
                    end   : subtitles[i].endTime / 1000,
                    text  : subtitles[i].text
                };
            }

            callback(subtitles);
        }
    };

    httpRequest.open('GET', url, true);
    httpRequest.send(null);
};

loadSRT('yellow/subs/Im_a_Yappie._ptbr.srt', function(subtitles) {
    var youtubeExternalSubtitle = new YoutubeExternalSubtitle.Subtitle(document.getElementById('video'), subtitles);
});
</script>
</figure>


# HTML-CAMP

A repository for learning HTML, CSS and BOOTSTRAP

```
1- Create an HTML Page
2- Install bootstrap through CDN, External CSS
3- Bootstrap Grid
4- Create A Nav-Bar
```

```
Why we use <!DOCTYPE html>?
Doctype stands for Document Type Declaration. It informs the web browser about the type and version of HTML used in building the web document.

What is a Head Tag?
The <head> element is a container for metadata (data about data) and is placed between the <html> tag and the <body> tag.Metadata typically define the document title, character set, styles, scripts, and other meta information.

what are the types of list in html?

1) unordered list = It used to group a related item not perticular group. eg:- Shoping list (Bread, milk, butter).
2) ordered list = It used to group a related items in a specific groups. eg:- Cooking instruction.
3) Description list = It will display the name/values pairs such terms and defination.

what are semantic HTML?

Semantic HTML elements are those that clearly describe their meaning in a human- and machine-readable way.
<article>	    Defines independent, self-contained content
<aside>	        Defines content aside from the page content
<details>	    Defines additional details that the user can view or hide
<figcaption>    Defines a caption for a <figure> element
<figure>	    Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
<footer>	    Defines a footer for a document or section
<header>	    Specifies a header for a document or section
<main>	        Specifies the main content of a document

what are the attributes of <video> semantic tags?

autoplay:- The second video are autometically play or start wthout stop the data or video.

autobuffer:-
The video will automatically begin buffering even if it's not set to automatically play.

controls:-
If this attribute is present, it will allow the user to control video playback, including volume, seeking, and pause/resume playback.

height:-
This attribute specifies the height of the video's display area, in CSS pixels.

loop:-
This Boolean attribute if specified, will allow video automatically seek back to the start after reaching at the end.

poster:-
This is a URL of an image to show until the user plays or seeks.

src:-
It will use to specify the URL for external source and resourse.

width:-
This attribute specifies the width of the video's display area, in CSS pixels.

why we should avoid inline styling?
1) Its not possible to overwrite the command of inline css.
2) One of the main reasons that inline styling is not a good choice for your application is because it does not support (or it has really poor support) for CSS features

what is rel?
The rel attribute defines the relationship between a linked resource and the current document.

why it is preffered to use external css over internal and inline css?

1) An external stylesheet is a standalone .css file that is linked from a web page. The advantage of external stylesheets is that it can be created once and the rules applied to multiple web pages.
2) An internal stylesheet holds CSS rules for the page in the head section of the HTML file. The rules only apply to that page.
3) Inline styles relate to a specific HTML tag, using a style attribute with a CSS rule to style a specific page element.

if poster attribute is not provided in video semantic HTML tag what will be shown until the video is not played?

The poster attribute specifies an image to be shown while the video is downloading, or until the user hits the play button. If this is not included, the first frame of the video will be used instead

what are block element and what are inline elements in HTML?

A block-level element always starts on a new line and takes up the full width available.

<div> <address> <article> <table> <tfoot> <ul> <video>

An inline element does not start on a new line and it only takes up as much width as necessary.

<samp> <script> <select> <small> <span> <strong> <sub> <object>
What are pseudo selector and pseudo classes?

A pseudo-class is used to define a special state of an element.
Eg:-Style an element when a user mouses over it.
A pseudo-element is used to style specified parts of an element.
Style the first letter, or line, of an element.

```

```
!impoertant tag has the topmost priority after that inline css has the most priority after that internal css than at last external css
class attribute is reusable and two element can have same classes but id is unique.
```

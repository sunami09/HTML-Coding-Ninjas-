
# HTML (Coding Ninjas)

HTML document is a text document saved with the extension .html or .htm that
contains texts and some tags written between "< >" which give the instructions needed
to configure the web page.

## Authors

- [Sunami Dasgupta](https://www.github.com/Sunami09)

- [Soham Das](https://github.com/fatemaker254)



-----------------------------------------------------------------




## Roadmap

- Intro to HTML.

- HTML Tags.

- HTML Use with Other Components.

- HTML Tables.

- HTML Forms.

- Fun with HTML.

- Major Project I.

- Major Project II.


---------------------------------------------------------------------------------------

### Introduction to HTML

**Overview**
- HTML stands for Hyper Text Markup Language.
- HTML describes the structure of web pages using markup.
- HTML is used to provide the content(words, images, audio, video, and so on) to the web pages.
- HTML is a tag-based language. They are defined within the angle brackets(< >)
- HTML files can be created using a text editor.

**Sample HTML document**

- Source file saved as index.html.

``` 
<!DOCTYPE html>
<html>

    <head>
        <title> Coding Ninjas </title>
    </head>

    <body>
        <h1>Welcome to Coding Ninjas ! </h1>
        <p> Let's Start Learning </p>
    </body>

</html>
```
- Output of the source file.

![Capture](https://user-images.githubusercontent.com/66564001/157053285-6ab83565-aaff-48de-9107-7876be4d5b4e.PNG)
```
- <!DOCTYPE html> tells the browser that the file being displayed is HTML5 page.
- <html> meant to contain all the HTML data and is the start of an HTML document.
- <head> provides information about the document. It is not displayed in the browser window.
- <title> provides a title for the document.
- <body> contains everything visible on the web page, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- <h1> element defines a large heading.
- <p> element defines a paragraph.
```

**Questions**
- What can be the possible extension for the HTML5 file?
- What is the correct syntax for writing ‘doctype’ in HTML5?
- What is the function of the title tags?

----------------------------------------------------

### HTML Tags and Elements

**Tags**\
Tags define all elements of the document, i.e. they give meaning to the plain
text of HTML.
```
- HTML tags are surrounded by the two characters < and > (They are called angle brackets).
- The tag name can either start from an alphabet or an underscore( _ ).
- The text between the start and end tags is the element content.
- Tags with an opening and closing can have any number of tags within themselves.
- HTML tags are not case sensitive, <p> means the same as <P>.
- HTML tags normally comes in pairs(container tags), i.e. both opening and closing(it is the same, just the name of the tag with the character '/ ' in the beginning) tag
- Eg: <html> and </html> is a tag that comes in pair.
- E.g., <br> does not have a closing tag.

NOTE : You might come across "self-closing" tags, whereby a br tag, for, e.g.., will look
like <br/> instead of simply <br>.
```

**Headings**
- Sample code for H tags

```
<!DOCTYPE html>
<html lang="en">

    <head>
        <title>Headings</title>
    </head>

    <body>
        <h1>This is Heading 1.</h1>
        <h2>This is Heading 2.</h2>
        <h3>This is Heading 3.</h3>
        <h4>This is Heading 4.</h4>
        <h5>This is Heading 5.</h5>
        <h6>This is Heading 6.</h6>
    </body>

</html>

```



- Output:

![Capture](https://user-images.githubusercontent.com/66564001/157067157-5686c734-557c-484f-af37-67b58588a730.PNG)

**Points to Remember**
- In HTML, tags that include both start and end tag are called - container tags.
- Tags are case insensetive.

**Images**

With HTML you can also display images in a document. In HTML, images are defined
with the `<img>` tag. `<img>` tag is a self-closing tag which means that it doesn't contain the closing
tag.

- Source Code:
```
<!DOCTYPE html>
<html lang="en">

    <head>
        <title>My Image</title>
    </head>

    <body>
        <img src="mypic.jfif" alt="My Image">
    </body>
</html>

```
- Output:

![Capture](https://user-images.githubusercontent.com/66564001/157243695-09445c9b-188e-4ce0-8109-d0e75ed88e78.PNG)


Here the `src` attribute tells the browser where to find the image or where is the image located. The `alt` attribute act as a safety net, if the browser can't find the image then it will show the given text.

We can also adjust height and width of the image using `height` and `width` attribute.\
Example: `<img src="images/logo.png" alt="Coding Ninjas image" height="500" width="500">`

Instead of assigning a image address located in our system we can also give the web adress of the image.\
Example: `<img src = “https://files.codingninjas.in/0000000000000723.jpg”>`



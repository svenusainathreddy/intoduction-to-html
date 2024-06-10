# intoduction-to-html
<!-- <!DOCTYPE html>THIS SPECIFIES THAT THE DOCUMENT IS THE HTML FORMAT -->
<!DOCTYPE html>
<!-- <html lang="en">THIS SPECIFIES THAT THE FORAMT IS USED IN THE ENGLISH LANGUAGE  (LANG IS AN ATTRIBUTE & HTML IS AN TAG) -->
<html lang="en">

<head>
    <!-- THESE ARE ALL THE META TAGS THAT ARE USED IN THE WEBSITE i.e (LINKS,DESCRIPTIONS,TITILE,ETC..... ) -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description"
        content="introduction about html in the easy way for the begginers easy to learn and practice">
    <title>INTRODUCTION</title>
    <!--LINK FOR CSS EXTERNAL FILE -->
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!--THE MAIN CONTENT GOES HEREALL THE HEADINGS(1-6) PARAGRAPHS ANCHORTAGS ETC..   -->

    <!-- HEADINGS -->
    <H1>EXAPMLE OF HEADINGS</H1>

    <h1>helo welcome to the world of web devolepmennt</h1>
    <h2>helo welcome to the world of web devolepmennt</h2>
    <h3>helo welcome to the world of web devolepmennt</h3>
    <h4>helo welcome to the world of web devolepmennt</h4>
    <h5>helo welcome to the world of web devolepmennt</h5>
    <h6>helo welcome to the world of web devolepmennt</h6>


    <!-- PARAGRAPHS -->
    <H1>EXAPMLE OF PARAS</H1>

    <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugiat excepturi quibusdam deserunt porro nulla ex enim
        consectetur! Autem, totam! Consequuntur?</P>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt, fugit? </p>

    <!-- Anchor tags -->
    <H1>EXAPMLE OF ANCHOR TAGS</H1>

    <!-- if we gIve target then it will open on the new tab else it will open in the same tab -->
    <a target="_blank" href="https://www.google.com">GOOGLE</a><br>
    <a href="https://www.facebook.com">FACEBOK</a><br>
    <a href="https://www.youtube.com">YOUTUBE</a><br>
    <a href="https://www.github.com/CodeWithHarry">CODE</a><br>
    <a href="https://www.CodeWithHarry.com">ALL PDF AND CHEATSHEETS</a><br>
    <a href="https://computersadda.com">FOR ALL VEDIO TUTORIALS AND NOTES</a><br><br>

    <!-- IMAGES -->
    <H1>EXAPMLE OF IMAGES</H1>

    <img height="500" src="images/bg.jpg" alt="bike images">
    <img width="300" src="images/icon.png" alt="icon of M">
    <img height="200" src="images/thanku.png" alt="THANKU IMAGES">
    <BR></BR>


    <!-- TABLE TAGS -->
    <H1>EXAMPLE OF TABLES</H1>
    <table>
        <caption>EMPLOYEE DETAILS</caption>
        <tr>
            <th>NAME</th>
            <th>DESIGNATON</th>
            <th>LANGUAGE</th>
        </tr>

        <tr>
            <td>MANJU</td>
            <td>PROGRAMMER</td>
            <td>ENGLISH</td>
        </tr>


        <tr>
            <td>RAJU</td>
            <td>DESIGNER</td>
            <td>PS</td>
        </tr>

        <tr>
            <td>MANJU</td>
            <td>TESTER</td>
            <td>KANADA</td>
        </tr>

        <tr>
            <td>SAMM</td>
            <td>DEVOLEPR</td>
            <td>HINDI</td>
        </tr>

    </table>
    <BR><BR></BR></BR>



    <table>
        <caption>TIMETABLE </caption>
        <tr>
            <th>DAY/TIME</th>
            <th>9:00-9:50</th>
            <th>9:50-10:40</th>
            <th rowspan="7">TEA BREAK</th>
            <th>11:00-11:50</th>
            <th>11:50-12:40</th>
            <th rowspan="7">TEA BREAK</th>
            <th>1:50-2:40</th>
            <th>2:40-3:30</th>
            <th>3:30-4:20</th>
        </tr>

        <tr>
            <td>mon</td>
            <td>p$s</td>
            <td>p&s</td>
            <td>DBMS</td>
            <td>SE</td>
            <td>PYP</td>
            <td>CO</td>
            <td>OS</td>
        </tr>

        <tr>
            <td>tues</td>
            <td>p$s</td>
            <td>p&s</td>
            <td colspan="2">DBMS</td>
            <td>SE</td>
            <td>PYP</td>
            <td>CO</td>
        </tr>
        <tr>
            <td>wed</td>
            <td>p$s</td>
            <td>p&s</td>
            <td>DBMS</td>
            <td>SE</td>
            <td>PYP</td>
            <td>CO</td>
            <td>OS</td>
        </tr>
        <tr>
            <td>thurs</td>
            <td>p$s</td>
            <td>p&s</td>
            <td colspan="2">PYP LAB</td>
            <td>SE</td>
            <td>PYP</td>
            <td>CO</td>
        </tr>
        <tr>
            <td>fri</td>
            <td>p$s</td>
            <td>p&s</td>
            <td>DBMS</td>
            <td>SE</td>
            <td>PYP</td>
            <td>CO</td>
            <td>OS</td>
        </tr>
        <tr>
            <td>sat</td>
            <td>p$s</td>
            <td>p&s</td>
            <td>DBMS</td>
            <td>SE</td>
            <td colspan="3">OS LAB</td>
        </tr>
    </table>
    <BR></BR>

    <table>
        <CAption>EXAPMLE FROM GOOGLE</CAption>
        <tr>
            <td rowspan="3">DAY</td>
            <td colspan="3">SEMINAR
            </td>
        </tr>

        <tr>
            <td colspan="2">SCHEDULE </td>
            <TD rowspan="2"> TOPIC</TD>
        </tr>
        <tr>
            <td>BEGIN</td>
            <TD>END</TD>
        </tr>
        <tr>
            <td>MONDAY</td>
            <td>8:00AM</td>
            <td>5:00PM</td>
            <TD>INTRODUCTION TO XML</TD>
        </tr>

        <TR>
            <TD rowspan="3">TUESDAY</TD>
            <TD>8:00AM</TD>
            <TD>8:00AM</TD>
            <TD>INTRODUCTION TO XML</TD>
        </TR>

        <TR>
            <TD>8:00AM</TD>
            <TD>8:00AM</TD>
            <TD>INTRODUCTION TO XML</TD>
        </TR>
        <TR>
            <TD>8:00AM</TD>
            <TD>8:00AM</TD>
            <TD>INTRODUCTION TO XML</TD>
        </TR>

    </table>



    <!-- LISTS--- ARE OF TWO TYPES ORDERES LISTS AND UNORDERED LISTS -->
    <H1>EXAMPLE OF LISTS</H1>

    <ol type="1" start="11"> <!--ORDERD LISTS TYPE=I i A a 1-->
        <li>tea</li>
        <li>cofee</li>
        <li>black tea</li>
        <li>honeytea</li>
        <li>badam tea</li>
        <li>ragi malt</li>
        <li>cold coffee</li>
        <li>boost</li>
        <li>horlicks</li>
        <li>bounvita</li>
    </ol>

    <ul type="circle"><!--UNORDERD LISTS   type="circle",square,disc-->
        <li>tea</li>
        <li>cofee</li>
        <li>black tea</li>
        <li>honeytea</li>
        <li>badam tea</li>
        <li>ragi malt</li>
        <li>cold coffee</li>
        <li>boost</li>
        <li>horlicks</li>
        <li>bounvita</li>
    </ul>


    <dl>DEFINTION LISTS</dl> <!--definintion-list , data-term , data-definition -->
    <dt>TEA</dt>
    <dd>RED COLOR HOT</dd>

    <dt>COFEE</dt>
    <dd>WHITE COLOR COLD</dd>

    <dt>BOOST</dt>
    <dd>BOOST IS THR SECRETRT OF MY ENERGY</dd>

    <!-- FORMS -->

    <h1>EXAMPLE OF FORMS</h1>
    <div>
        <label for="name">Enter your username:</label>
        <input type="text" id="name" placeholder="Enter your username" autofocus>
    </div>

    <div>
        <label for="password">Enter your password:</label>
        <input type="password" id="password" placeholder="Enter your password">
    </div>
    <div>
        <label for="gender">Gender:</label>
        <input type="radio" name="gender" id="male" value="male">
        <label for="male">Male</label>
        <input type="radio" name="gender" id="female" value="Female">
        <label for="female">Female</label>
    </div>
    <div>
        <label for="hobbies">Hobbies:</label>
        <input type="checkbox" name="hobbies" id="playing" value="playing">
        <label for="playing">Playing</label>
        <input type="checkbox" name="hobbies" id="drawing" value="drawing">
        <label for="drawing">drawing</label>
        <input type="checkbox" name="hobbies" id="swimming" value="swimming">
        <label for="swimming">swimming</label>
        <input type="checkbox" name="hobbies" id="dancing" value="dancing">
        <label for="dancing">dancing</label>
    </div>
    <div>
        <select name="country">
            <option value="enter ur country">--Enter ur Country--</option>
            <option value="india">india</option>
            <option value="asia">asia</option>
            <option value="pakistan">pakistan</option>
            <option value="america">america</option>
        </select>
    </div>
    <div>
        <label for="comments">Enter ur Commnets Here:</label><br>
        <textarea name="comments" id="" cols="*" rows="*" placeholder="Enter ur Comments here......"></textarea>
    </div>

    <h1>EXMPLE OF INLINE AND BLOCK ELEMENTS</h1>
    <!-- inline and block elements     
<p>: Paragraph.
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>: Headings.
<ul>: Unordered list.
<ol>: Ordered list.
<li>: List item.
<form>: A section containing form controls.
<table>: Table.
<section>: A standalone section of a document.
<header>: A container for introductory content or a set of navigational links.
<footer>: Footer of a section or page.
<nav>: A section of a page that contains navigation links.
<article>: A self-contained composition in a document.
<aside>: A section of a page that contains information indirectly related to the main content.
<main>: The main content of a document.
<fieldset>: A set of form controls grouped under a common name.
<blockquote>: A block of text that is a quotation from another source.
<pre>: Preformatted text.
<canvas>: A container used to draw graphics via JavaScript.
<dl>: Description list.
<dt>: Term in a description list.
<dd>: Description in a description list.
<figure>: Any content that is referenced from the main content.
<figcaption>: A caption for a <figure> element.
<address>: Contact information for the author or owner of the document.
<hr>: A thematic break or a horizontal rule.
<tfoot>: Footer of a table.

Inline Elements (Most Commonly Used First)
<a>: Anchor or hyperlink.
<img>: Image.
<span>: Generic inline container.
<input>: Input field.
<label>: Label for a form element.
<strong>: Strong emphasis.
<em>: Emphasized text.
<br>: Line break.
<code>: Code snippet.
<b>: Bold text.
<i>: Italic text.
<u>: Underlined text.
<small>: Smaller text.
<sub>: Subscript.
<sup>: Superscript.
<mark>: Marked or highlighted text.
<q>: Short inline quotation.
<cite>: Citation.
<kbd>: Keyboard input.
<samp>: Sample output.
<var>: Variable in a mathematical expression or programming context.
<time>: Time.
<abbr>: Abbreviation.
<data>: Machine-readable translation of content.
<acronym>: Acronym (Not supported in HTML -->

    <P>INLINE ELEMENTS ARE THE ELEMENTS THAT OCCUPIES ONLY LIMITED SPACE </P>
    <H4>EXAPMLE</H4>
    <h5>anchor tag,img,br,i,b,u,small,big,sub,sup,q,marquee,cite,input,label,em.</h5>
    <a style="background-color: rgba(32, 255, 92, 0.807);" href="https://google.com">Google </a>
    <span style="background-color: rgb(208, 107, 127);">hey iam inline element</span>

    <P>BLOCK ELEMENTS ARE THE ELEMENTS THAT OCCUPIES WHOLE LINEL </P>
    <H4>EXAPMLE</H4>
    <h5>div,p,headings,ol,ul,li,forms,table,footer,header,dl,dt,dd.</h5>
    <p style="background-color: aqua;">hey i am BLOCK element</p>

    <!-- ID AND CLASSES -->
    <H1>ID AND CLASS SELECTORS</H1>
    <H3>ID SELECTOR:</H3>
    <P>ID selector is a selector that is useed to select only a SINGLE and UNIQUE element
        here mainly ID SELECTOR USES # FOR THE SELECTION
        FOR EX: #h1,#p,#div....
        <!--h1 id="mydiv"></h1>
       #mydiv{
            background-color:yellow;
        } -->
    </P>
    <P> CLASS selector is a selector that is useed to select MULTIPLE and SEVERAL element
        here mainly CLASS SELECTOR USES .FOR THE SELECTION
        FOR EX: .h1 .p .div
        <!--p class="p1"></p>
        <   h2 class="p1"></h2>
        <   h3 class="p1"></h3>
       .p1{
            background-color:red;
        } -->
    </P>

    <!-- AUDIO  VEDIO  MEDIA FRAMES -->
    <H1>AUDIO VIDEO AND MEDIA</H1>

    <h3>video examples....</h3>
    <video src="images/video5.mp4" height="222" width="500" controls loop muted poster="images/icon.png"
        preload="auto"></video>
    <video src="images/video4.mp4" height="555" width="555" controls loop muted autoplay poster="images/bg.jpg"></video>
    <h2>svg example </h2>
    <!--SVG(SCALABLE VECTOR GRAPHICS) IS THE FORMAT THAT IS USED TO CREATE THE IMAGES IN HIGH QUALITY   -->
    <svg height="100" width="100">
        <circle cx="50" cy="59" r="40" stroke="black" fill="red" stroke-width="3" />
    </svg>

    <h2>Audio examples</h2>
    <audio src="images/Radha Krishna.mp3" controls loop muted autoplay></audio>

    <!-- frames -->
    <h2>Iframes</h2>
    <iframe src="https://www.youtube.com/" frameborder="0"></iframe>
    <iframe src="https://www.codewithharry.com/tutorial/html-iframes/" frameborder="20"></iframe>
    <iframe src="https://www.codewithharry.com/tutorial/html-iframes/" frameborder="0" allowfullscreen></iframe>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/fhoDRB53DwY?si=WNbYft6HAYSic_YJ"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen></iframe>

    <!-- SEMANTIC TAGS -->

    <!-- Semantic tags add meaning to your HTML. They tell both the browser and the developer what kind of content is being presented.

        Here are some of the key semantic tags you must know about:

        <header>: Used to represent the top section of a web page, often containing headings, logos, and navigation.

        <nav>: Signifies a navigation menu on a web page.

        <article>: Indicates a self-contained piece of content, such as a blog post or news article.

        <section>: Represents a thematic grouping of content on a web page.

        <aside>: Typically used for sidebars or content that is tangentially related to the main content.

        <footer>: Represents the footer of a web page, usually containing copyright information and contact details.

        <figure> and <figcaption>: Used for embedding images, diagrams, or charts, along with a caption.

        <main>: Signifies the main content area of a web page.

        <time>: Used to represent time-related information, like dates and times. -->

    <h4>HERE SEMANTIC TAGS ARE ONE OF THE MOST IMP TO CREATE AND SPECIFY THE HEADER NAVBAR MAIN CONTENT FOOTER
        examples----: TAGS : nav article section aside footer figure main time </h4>
    <strong>the main aim of semanitc tags is to represent the code in a structured manner by using semantic tags than
        the div span tags for all the content in the web page ---Why Use Semantic Tags?
        They enhance SEO, improve accessibility, and make your code easier to read and maintain.---</strong>
    <header>
        <header>
            <nav style="display: flex;">
                <p>this is the nav bar of the page</p>
                <ul>
                    <li><a href="home.html">Home</a></li>
                    <li><a href="about.html">about</a></li>
                    <li><a href="contact.html">contact</a></li>
                </ul>
                <aside>
                    ASIDE tag is used in the nav bar to display the content
                </aside>
            </nav>
            <main>
                <h5>this is the main content of the page</h5>
                <figure>
                    <img src="images/semantic tags.png" alt="semantic tags ">
                    <figcaption>this is the example of the semantic structure</figcaption>
                </figure>
                <article>
                    <h2>ARITCLE Title this is used to to keep the headings and titiles</h2>
                    <section>
                        <p> SECTION THIS IS USED TO WRITE THE PARAGRAPHS ABOUT THE TITLE IT IS USED TO DESCIRBE THE
                            TITLE </p>
                    </section>
                </article>
            </main>
        </header>

        <footer>
            <p>this is footer of the page</p>
        </footer>

        <!-- HTML ENTITIES -->
        <pre>
            &lt; for < &gt; for>
            &amp; for &
            &nbsp; for a non-breaking space
            &copy; for ©
        </pre>


        <!-- QUOTATION TAGS -->

        <blockquote>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sint culpa suscipit, illum, quas accusamus
            dolorum accusantium est omnis corporis quod, quae natus! Ex.</blockquote>

            <q>hey this is the quotation tag</q>

            <!-- CODE tags -->
            <p>code tags are used to display the code in the website i.e like w3schools.  code tag is used inside the pre tag</p>
            <pre>
                <code>
                    &lt; !DOCTYPE html>
                    &lt; html lang="en">
                    &lt; head>
                        &lt; meta charset="UTF-8">
                        &lt; meta name="viewport" content="width=device-width, initial-scale=1.0">
                       &lt; title>Document</title>
                    &lt; /head>
                    &lt; body>
                        
                    &lt; /body>
                   &lt; /html>
                </code>
                </pre>
        <h1>marquee Tags</h1>
        <marquee scroll-direction="left">hey this is the maquee tag</marquee>
        <!-- SCRIPT TAG -->
        <!-- IT IS  LINK FOR THE JAVA SCRIPT EXTERNAL FILE -->
        <script src="script.js"></script>
</body>
</html>
 <!-- END OF HTML INTRODUCTION -->

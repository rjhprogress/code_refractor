<p>View the Refractored Website Here: https://rjhprogress.github.io/code_refractor/</p>


<p>Existing code has been refactored to follow semantic structure of HTML elements. 
This is was done to ensure Web accessibility for all users. The semantic structure of HTML elements is an extremely important
consideration. It allows people with disabilities or social economic restrictions
to have access of the websites content. Codebase has also been made more efficient 
by consolidating CSS selectors and properties for long term sustainability. </p>

<p>The technologies used to build this website are HTML, and CSS.</p>

<p>These are semantic elements applied to the code casebase, which fall in sequential order:</p>

<textarea>
- <header></header>,
- <nav></nav>,
- <main></main>,
- <section></section>,
- <article></article>,
- <aside></aside>,
- <footer></footer>,
</textarea>


<h2>The codebase without accessibility is as follows:</h2>

<textarea>
<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horiseon</title>
</head>

<body>
    <div>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </div>
    <div class="hero">
    </div>
    <div>
        <div id="search-engine-optimization" class="service">
            <img src="./assets/images/search-engine-optimization.jpg" alt="Notebook with search engine optimization concepts on cover on a cluttered wooden table." class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </div>
        <div id="online-reputation-management" class="service">
            <img src="./assets/images/online-reputation-management.jpg" alt="Person checking cell phone while looking at a laptop showing a graph of increasing online reputation." class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </div>
        <div id="social-media-marketing" class="service">
            <img src="./assets/images/social-media-marketing.jpg" alt="Large solar panels in a green field of plants with a blue sky and light white clouds above it." class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </div>
    </div>
    <div class="benefits">
        <div class="benefit">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="Several people using devices sitting at a table cluttered with social media icons and actions such as Tweet, Share, and Like." />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="Black icon of a person with a lightbulb for a head emitting waves." />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="Black icon of a gear surrounded by three coins with dollar signs on them." />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </div>
    <div>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </div>
</body>

</html>
</textarea>

<h2>The codebase with accessibilty is as follows:</h2>
<textarea>
<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horiseon</title>
</head>

<body>
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
    <div class="hero">
    </div>
    <main>
        <section id="search-engine-optimization" class="service">
            <img src="./assets/images/search-engine-optimization.jpg" alt="Notebook with search engine optimization concepts on cover on a cluttered wooden table." class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
        <section id="online-reputation-management" class="service">
            <img src="./assets/images/online-reputation-management.jpg" alt="Person checking cell phone while looking at a laptop showing a graph of increasing online reputation." class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </section>
        <section id="social-media-marketing" class="service">
            <img src="./assets/images/social-media-marketing.jpg" alt="Large solar panels in a green field of plants with a blue sky and light white clouds above it." class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </section>
    </main>
    <aside class="benefits">
        <div class="benefit">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="Several people using devices sitting at a table cluttered with social media icons and actions such as Tweet, Share, and Like." />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
        <div class="benefit">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" alt="Black icon of a person with a lightbulb for a head emitting waves." />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
        <div class="benefit">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="Black icon of a gear surrounded by three coins with dollar signs on them." />
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </div>
    </aside>
    <footer>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
</body>

</html>

</textarea>

<p>View the Refractored Website Here: https://rjhprogress.github.io/code_refractor/</p>
<!-- ((! set title OCaml !)) ((! set core !)) -->
<header id="home-header">
    <div class="container">
        <div class="row">
            <h1 class="span9">OCaml is an industrial strength programming language supporting functional, imperative and object-oriented styles</h1>
            <div class="span3">
                <div>
                    <a class="btn" href="#">Download OCaml</a>
                </div>
            </div>
        </div>
    </div>
</header>
<div class="container">
    <div class="row home-hero">
        <div class="span8">
            <div class="row">
                <section class="span4 home-feature">
                    <a href="#">
                        <img src="/static/img/learn-large.png" alt="Learn">
                    </a>
                    <h1><a href="menu.html">Learn</a></h1>
                    <p>Lorem ipsum dolor sit amet, septum consectetur adipisicing elit, sed do eiusmod tempor incididunt ut.</p>
                </section>
                <section class="span4 home-feature">
                    <a href="documentation.html">
                        <img src="/static/img/documentation-large.png" alt="Documentation">
                    </a>
                    <h1><a href="#">Documentation</a></h1>
                    <p>Lorem ipsum dolor sit amet, septum consectetur adipisicing elit, sed do eiusmod tempor incididunt ut.</p>
                </section>
            </div>
            <div class="row">
                <section class="span4 home-feature">
                    <a href="platform.html">
                        <img src="/static/img/platform-large.png" alt="Platform">                    </a>
                    <h1><a href="#">Platform</a></h1>
                    <p>Lorem ipsum dolor sit amet, septum consectetur adipisicing elit, sed do eiusmod tempor incididunt ut.</p>
                </section>
                <section class="span4 home-feature">
                    <a href="menu.html">
                        <img src="/static/img/community-large.png" alt="Community">
                    </a>
                    <h1><a href="#">Community</a></h1>
                    <p>Lorem ipsum dolor sit amet, septum consectetur adipisicing elit, sed do eiusmod tempor incididunt ut.</p>
                </section>
            </div>
            <div id="home-learn">
                <a href="http://try.ocamlpro.com">
                    <img class="hidden-phone" src="/static/img/learn-ocaml.png" alt="">
                    Learn OCaml in your browser with TryOCaml
                </a>
            </div>
        </div>
        <section id="home-news" class="span4 condensed">
            <h1 class="ruled">
                <a href="#">
                    News
                </a>
                <a href="#">
                    <img src="/static/img/rss.png" alt="RSS">
                </a>
            </h1>
            <ul class="news-feed">
                <li class="announcement">
                    <article>
                        <h1><a href="#">OCaml Platform v0.1 available</a></h1>
                        <p>13 March 2013</p>
                        <a href="#">
                            <img src="/static/img/announcement.png" alt="Announcement">
                        </a>
                    </article>
                </li>
                    <li>
                        <article>
                            <h1><a href="#">First release of PPrint</a></h1>
                            <p>08 February 2013</p>
                            <a href="#">
                                <img src="/static/img/news.png" alt="News">
                            </a>
                        </article>
                    </li>
                    <li>
                        <article>
                            <h1><a href="#">First release of PPrint</a></h1>
                            <p>08 February 2013</p>
                            <a href="#">
                                <img src="/static/img/news.png" alt="News">
                            </a>
                        </article>
                    </li>
                    <li>
                        <article>
                            <h1><a href="#">First release of PPrint</a></h1>
                            <p>08 February 2013</p>
                            <a href="#">
                                <img src="/static/img/news.png" alt="News">
                            </a>
                        </article>
                    </li>
                    <li>
                        <article>
                            <h1><a href="#">First release of PPrint</a></h1>
                            <p>08 February 2013</p>
                            <a href="#">
                                <img src="/static/img/news.png" alt="News">
                            </a>
                        </article>
                    </li>
            </ul>
            <p><a href="#">More...</a></p>
        </section>
    </div>
    <div class="row">
        <section class="span6 condensed">
            <h1>A taste of OCaml</h1>
<pre class="listing"><code>(* Binary tree with leaves carrying an integer. *)
type tree = Leaf of int | Node of tree * tree

let rec exists_leaf test tree =
  match tree with
  | Leaf v -&gt; test v
  | Node (left, right) -&gt;
      exists_leaf test left
      || exists_leaf test right

let has_even_leaf tree =
  exists_leaf (fun n -&gt; n mod 2 = 0) tree</code></pre>
        </section>
        <section class="span6 condensed">
            <h1>Packages</h1>
<ul class="nav nav-tabs">
    <li class="active">
        <a href="#">Recent updates</a>
    </li>
    <li><a href="#">Most popular</a></li>
    <li><a href="#">Statistics</a></li>
</ul>
<table class="table table-bordered table-condensed table-hover">
    <thead>
        <tr>
            <th>Package</th>
            <th>Author</th>
            <th>Category</th>
            <th>Version</th>
            <th>Date</th>
        </tr>
    </thead>
    <tbody>
            <tr>
                <td><a href="#">obuild</a></td>
                <td><a href="#">foo</a></td>
                <td><a href="#">Tools</a></td>
                <td><a href="#">0.0.1</a></td>
                <td><a href="#">9:00  12 Feb 2013</a></td>
            </tr>
            <tr>
                <td><a href="#">obuild</a></td>
                <td><a href="#">foo</a></td>
                <td><a href="#">Tools</a></td>
                <td><a href="#">0.0.1</a></td>
                <td><a href="#">9:00  12 Feb 2013</a></td>
            </tr>
            <tr>
                <td><a href="#">obuild</a></td>
                <td><a href="#">foo</a></td>
                <td><a href="#">Tools</a></td>
                <td><a href="#">0.0.1</a></td>
                <td><a href="#">9:00  12 Feb 2013</a></td>
            </tr>
            <tr>
                <td><a href="#">obuild</a></td>
                <td><a href="#">foo</a></td>
                <td><a href="#">Tools</a></td>
                <td><a href="#">0.0.1</a></td>
                <td><a href="#">9:00  12 Feb 2013</a></td>
            </tr>
            <tr>
                <td><a href="#">obuild</a></td>
                <td><a href="#">foo</a></td>
                <td><a href="#">Tools</a></td>
                <td><a href="#">0.0.1</a></td>
                <td><a href="#">9:00  12 Feb 2013</a></td>
            </tr>

            <tr>
                <td><a href="#">obuild</a></td>
                <td><a href="#">foo</a></td>
                <td><a href="#">Tools</a></td>
                <td><a href="#">0.0.1</a></td>
                <td><a href="#">9:00  12 Feb 2013</a></td>
            </tr>
    </tbody>
</table>
        </section>
    </div>
</div>
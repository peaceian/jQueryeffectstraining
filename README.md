# jQueryeffectstraining
This project is made by using jQuery to train the effects.<br>
jQuery effects: $ ( selector).slideToggle([duration][,complete])<br>
 &lt;section class="row"&gt;<br>
        &lt;div class="column"&gt;<br>
            &lt;div class="card"&gt;<br>
                &lt;div class="image-frame"&gt;<br>
                    &lt;img src="image2.jpg" alt="Tac" style="width:100%;"&gt;<br>
                    &lt;div class="image-caption"&gt;<br>
                        &lt;h4&gt;Alexis Ren&lt;/h4&gt;<br>
                        &lt;p&gt;CEO & Founder&lt;/p&gt;<br>
                    &lt;/div&gt;<br>
                &lt;/div&gt;<br>
                &lt;div class="container"&gt;<br>
                    &lt;h2&gt;Alexis Ren&lt;/h2&gt;<br>
                    &lt;p class="title"&gt;CEO & Founder&lt;/p&gt;<br>
                    &lt;p&gt;略&lt;/p&gt;<br>
                    &lt;a href="#"&gt;&lt;i class="fa-brands fa-facebook fa-fw fa-2x"&gt;&lt;/i&gt;&lt;/a&gt;<br>
                    &lt;a href="#"&gt;&lt;i class="fa-brands fa-instagram-square fa-fw fa-2x"&gt;&lt;/i&gt;&lt;/a&gt;<br>
                    &lt;p&gt;&lt;button class="button"&gt;Read More&lt;/button&gt;&lt;/p&gt;<br>
                &lt;/div&gt;<br>
            &lt;/div&gt;<br>
        &lt;/div&gt;<br><br><br>
$ (document).ready(function () {<br>
            $ (".image-frame").hover(function () {/*the same effect with :hover*/<br>
                $ ( ".image-caption", this).slideToggle("slow");<br>
            }, function () {<br>
                $ (".image-caption", this).slideToggle("slow");<br>
            });<br>
        });<br>

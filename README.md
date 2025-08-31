<b>Examples / Slide.html :נמצאת במיקום הזה multi-swipers הפונקציה של</b></br>
<br>
class="swiper multi-swipers <b>swiper-on-mobile</b>" // max-width: 767px <br>
OR<br>
class="swiper multi-swipers <b>swiper-on-tablet</b>" // max-width: 991px <br>
OR<br>
class="swiper multi-swipers <b>swiper-on-desktop</b>" // min-width: 768px <br>
<br>
&lt;div <br>
class="swiper <b>multi-swipers</b>" <br>
data-items="1" <br>
data-autoplay="3000" <span style="color:green;">// seconds</span> <br>
data-arrows="1" <span style="color:green;">// true</span> <br>
data-nested="1" <span style="color:green;">// true</span> <br>
data-speed="1" <span style="color:green;">// miliseconds</span> <br>
data-margin="20" <span style="color:green;">// spaceBetween</span> <br>
data-pagination="1" <span style="color:green;">// true</span> <br>
data-pagination-type="Progressbar" <br>
data-center-slides="1" <span style="color:green;">// true</span> <br>
data-effect="fade" <br>
data-start="2" <span style="color:green;">// start from slide 2</span> <br>
data-rtl="1" <span style="color:green;">// true</span> <br>
data-loop="1" <span style="color:green;">// true</span> <br>
data-breakpoints-992='{"slidesPerView": 4}' <span style="color:green;">// min-width: 992px</span> <br>
data-breakpoints-768='{"slidesPerView": 3}' <span style="color:green;">// min-width: 768px</span> <br>
data-breakpoints-600='{"slidesPerView": 2}' <span style="color:green;">// min-width: 600px</span> <br>
&gt; <br>
&nbsp;&nbsp;&lt;div class="swiper-wrapper"&gt; <br>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;div class="swiper-slide"&gt; 1 &lt;/div&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;div class="swiper-slide"&gt; 2 &lt;/div&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;div class="swiper-slide"&gt; 3 &lt;/div&gt;<br>
    <br>
&nbsp;&lt;/div&gt;<br>
<br>
&lt;div class="swiper-pagination"&gt;&lt;/div&gt;<br>
<br>
<b>swiper-wrap אפשר להוציא את הכפתורים כל עוד הם נמצאים בתוך קלאס</b><br>
&nbsp;&nbsp;&lt;button type="button" class="next"&gt;Next&lt;/button&gt;<br>
&nbsp;&nbsp;&lt;button type="button" class="prev"&gt;Prev&lt;/button&gt;<br>
 <br>
&lt;/div&gt;

<pre>
Color Space : 1.2 : 2012.09.01 : http://mudcu.be
----------------------------------------------------
RGBA &lt;-&gt; HSLA  &lt;-&gt; W3
RGBA &lt;-&gt; HSVA
RGBA &lt;-&gt; CMY   &lt;-&gt; CMYK
RGBA &lt;-&gt; HEX24 &lt;-&gt; W3
RGBA &lt;-&gt; HEX32
RGBA &lt;-&gt; W3
----------------------------------------------------
Examples
----------------------------------------------------
Color.Space(0x99ff0000, "HEX32&gt;RGBA&gt;HSLA&gt;W3"); // outputs "hsla(60,100%,17%,0.6)"
Color.Space(0xFF0000, "HEX24&gt;RGB&gt;HSL"); // convert HEX24 to HSL object.
Color.Space("hsla(120, 100%, 50%, 1)", "W3&gt;HSLA"); // convert W3 string to HSLA object.
----------------------------------------------------
W3 values
----------------------------------------------------
rgb(255,0,0)
rgba(255,0,0,1)
rgb(100%,0%,0%)
rgba(100%,0%,0%,1)
hsl(120, 100%, 50%)
hsla(120, 100%, 50%, 1)
#000000
</pre>
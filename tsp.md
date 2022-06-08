
<meta name="generator" content="Jekyll v3.9.0" />
<meta property="og:title" content="globish" />
<meta property="og:locale" content="en_US" />
<meta name="description" content="Globish 1500単語の日英レベルCSVデータ" />
<meta property="og:description" content="Globish 1500単語の日英レベルCSVデータ" />
<link rel="canonical" href="https://taisukef.github.io/globish/" />
<meta property="og:url" content="https://taisukef.github.io/globish/" />
<meta property="og:site_name" content="globish" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="globish" />

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      

<h2 id="csv">CSV</h2>
<p>https://taisukef.github.io/globish/globishwords.csv</p>

<h2 id="how-to-use-in-javascript">How to use in JavaScript</h2>
<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>&lt;script type="module"&gt;
import { CSV } from "https://code4sabae.github.io/js/CSV.js";
 
window.onload = async () =&gt; {
  const csv = await CSV.fetch("https://taisukef.github.io/globish/globishwords.csv");
  console.log(csv);
 	const words = CSV.toJSON(csv);
  console.log(words);
};
&lt;/script&gt;
</code></pre></div></div>

<h2 id="how-to-use-on-deno">How to use on Deno</h2>
<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>import { CSV } from "https://code4sabae.github.io/js/CSV.js";
 
const csv = await CSV.fetch("https://taisukef.github.io/globish/globishwords.csv");
console.log(csv);
const words = CSV.toJSON(csv);
console.log(words);
</code></pre></div></div>

<h2 id="samples">samples</h2>
<p>https://taisukef.github.io/TypingGame/<br />
タイピングゲーム</p>


      
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
    
  </body>
</html>

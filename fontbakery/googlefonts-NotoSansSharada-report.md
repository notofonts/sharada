## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[6] NotoSansSharada-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/sharada.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansSharada/googlefonts/ttf/NotoSansSharada-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/sharada.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">𑆱𑆴𑇌𑆱𑆶𑇌</span> (Issue #1333)</li>


<pre>Expected: I=0+224|ShortVowelMark=0@-97,0+0|Sa=0+700|Sa=3+700|U.alt4=3@-248,0+0|ShortVowelMark=3@-438,-310+0</pre>



<pre>Got     : I=0+224|ShortVowelMark=0@122,0+0|Sa=0+700|Sa=3+700|U.alt4=3@-248,0+0|ShortVowelMark=3@-438,-310+0</pre>



<pre>                                   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1624 2380" transform="matrix(1 0 0 -1 0 0)">
<path d="M84.0,0.0L84.0,550.0L24.0,550.0L24.0,625.0L84.0,625.0L84.0,690.0Q84.0,736.0 104.0,779.5Q124.0,823.0 167.0,851.5Q210.0,880.0 278.0,880.0Q381.0,880.0 468.0,806.5Q555.0,733.0 625.0,593.0L543.0,593.0Q489.0,688.0 426.5,746.5Q364.0,805.0 280.0,805.0Q226.0,805.0 197.5,771.0Q169.0,737.0 169.0,688.0L169.0,625.0L296.0,625.0L296.0,550.0L169.0,550.0L169.0,0.0L84.0,0.0Z"  transform="translate(0, 955)"/>
<path d="M154.0,-265.0L-46.0,-87.0L3.0,-37.0L203.0,-215.0L154.0,-265.0Z"  transform="translate(346, 955)"/>
<path d="M532.0,0.0L532.0,242.0L253.0,242.0L253.0,192.0Q253.0,166.0 244.0,141.0Q235.0,116.0 209.0,116.0Q196.0,116.0 170.5,130.0Q145.0,144.0 117.5,165.5Q90.0,187.0 70.5,210.0Q51.0,233.0 51.0,251.0Q51.0,273.0 71.5,287.0Q92.0,301.0 119.5,309.0Q147.0,317.0 168.0,321.0L168.0,550.0L24.0,550.0L24.0,625.0L253.0,625.0L253.0,317.0L532.0,317.0L532.0,625.0L676.0,625.0L676.0,550.0L617.0,550.0L617.0,0.0L532.0,0.0Z"  transform="translate(224, 955)"/>
<path d="M532.0,0.0L532.0,242.0L253.0,242.0L253.0,192.0Q253.0,166.0 244.0,141.0Q235.0,116.0 209.0,116.0Q196.0,116.0 170.5,130.0Q145.0,144.0 117.5,165.5Q90.0,187.0 70.5,210.0Q51.0,233.0 51.0,251.0Q51.0,273.0 71.5,287.0Q92.0,301.0 119.5,309.0Q147.0,317.0 168.0,321.0L168.0,550.0L24.0,550.0L24.0,625.0L253.0,625.0L253.0,317.0L532.0,317.0L532.0,625.0L676.0,625.0L676.0,550.0L617.0,550.0L617.0,0.0L532.0,0.0Z"  transform="translate(924, 955)"/>
<path d="M-16.0,-250.0Q-60.0,-250.0 -104.0,-239.5Q-148.0,-229.0 -186.0,-207.0L-150.0,-148.0Q-113.0,-165.0 -80.0,-171.0Q-47.0,-177.0 -18.0,-177.0Q25.0,-177.0 51.5,-160.5Q78.0,-144.0 78.0,-108.0L78.0,35.0L163.0,35.0L163.0,-112.0Q163.0,-176.0 113.5,-213.0Q64.0,-250.0 -16.0,-250.0Z"  transform="translate(1376, 955)"/>
<path d="M154.0,-265.0L-46.0,-87.0L3.0,-37.0L203.0,-215.0L154.0,-265.0Z"  transform="translate(1186, 645)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1624 2380" transform="matrix(1 0 0 -1 0 0)">
<path d="M84.0,0.0L84.0,550.0L24.0,550.0L24.0,625.0L84.0,625.0L84.0,690.0Q84.0,736.0 104.0,779.5Q124.0,823.0 167.0,851.5Q210.0,880.0 278.0,880.0Q381.0,880.0 468.0,806.5Q555.0,733.0 625.0,593.0L543.0,593.0Q489.0,688.0 426.5,746.5Q364.0,805.0 280.0,805.0Q226.0,805.0 197.5,771.0Q169.0,737.0 169.0,688.0L169.0,625.0L296.0,625.0L296.0,550.0L169.0,550.0L169.0,0.0L84.0,0.0Z"  transform="translate(0, 955)"/>
<path d="M154.0,-265.0L-46.0,-87.0L3.0,-37.0L203.0,-215.0L154.0,-265.0Z"  transform="translate(127, 955)"/>
<path d="M532.0,0.0L532.0,242.0L253.0,242.0L253.0,192.0Q253.0,166.0 244.0,141.0Q235.0,116.0 209.0,116.0Q196.0,116.0 170.5,130.0Q145.0,144.0 117.5,165.5Q90.0,187.0 70.5,210.0Q51.0,233.0 51.0,251.0Q51.0,273.0 71.5,287.0Q92.0,301.0 119.5,309.0Q147.0,317.0 168.0,321.0L168.0,550.0L24.0,550.0L24.0,625.0L253.0,625.0L253.0,317.0L532.0,317.0L532.0,625.0L676.0,625.0L676.0,550.0L617.0,550.0L617.0,0.0L532.0,0.0Z"  transform="translate(224, 955)"/>
<path d="M532.0,0.0L532.0,242.0L253.0,242.0L253.0,192.0Q253.0,166.0 244.0,141.0Q235.0,116.0 209.0,116.0Q196.0,116.0 170.5,130.0Q145.0,144.0 117.5,165.5Q90.0,187.0 70.5,210.0Q51.0,233.0 51.0,251.0Q51.0,273.0 71.5,287.0Q92.0,301.0 119.5,309.0Q147.0,317.0 168.0,321.0L168.0,550.0L24.0,550.0L24.0,625.0L253.0,625.0L253.0,317.0L532.0,317.0L532.0,625.0L676.0,625.0L676.0,550.0L617.0,550.0L617.0,0.0L532.0,0.0Z"  transform="translate(924, 955)"/>
<path d="M-16.0,-250.0Q-60.0,-250.0 -104.0,-239.5Q-148.0,-229.0 -186.0,-207.0L-150.0,-148.0Q-113.0,-165.0 -80.0,-171.0Q-47.0,-177.0 -18.0,-177.0Q25.0,-177.0 51.5,-160.5Q78.0,-144.0 78.0,-108.0L78.0,35.0L163.0,35.0L163.0,-112.0Q163.0,-176.0 113.5,-213.0Q64.0,-250.0 -16.0,-250.0Z"  transform="translate(1376, 955)"/>
<path d="M154.0,-265.0L-46.0,-87.0L3.0,-37.0L203.0,-215.0L154.0,-265.0Z"  transform="translate(1186, 645)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* SutraMark
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NullMark
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Ograve	Contours detected: 2	Expected: 3

	- Glyph name: Oacute	Contours detected: 2	Expected: 3

	- Glyph name: Ocircumflex	Contours detected: 2	Expected: 3

	- Glyph name: Otilde	Contours detected: 2	Expected: 3

	- Glyph name: Odieresis	Contours detected: 3	Expected: 4

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Omacron	Contours detected: 2	Expected: 3

	- Glyph name: Ohungarumlaut	Contours detected: 3	Expected: 4

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1 

	- And 10 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* And 81 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 5 | 110 | 7 | 104 | 0 |
| 0% | 0% | 2% | 48% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**

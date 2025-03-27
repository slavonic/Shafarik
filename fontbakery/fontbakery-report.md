## FontBakery report

fontbakery version: 0.13.1





## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] Shafarik-Regular.ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Check base characters have non-zero advance width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#base-has-width">base_has_width</a></summary>
    <div>







* 💥 **ERROR** <p>Failed with AttributeError: 'CheckRunContext' object has no attribute 'get'</p>
<pre><code>  File &quot;/home/runner/work/Shafarik/Shafarik/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py&quot;, line 222, in _run_check
    subresults = list(subresults)
  File &quot;/home/runner/work/Shafarik/Shafarik/venv-test/lib/python3.10/site-packages/fontbakery/checks/base_has_width.py&quot;, line 46, in check_base_has_width
    problems = bullet_list(context, problems)
  File &quot;/home/runner/work/Shafarik/Shafarik/venv-test/lib/python3.10/site-packages/fontbakery/utils.py&quot;, line 155, in bullet_list
    return f&quot;{indentation}{bullet} &quot; + pretty_print_list(
  File &quot;/home/runner/work/Shafarik/Shafarik/venv-test/lib/python3.10/site-packages/fontbakery/utils.py&quot;, line 140, in pretty_print_list
    if config.get(&quot;full_lists&quot;):

</code></pre>
 [code: failed-check]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[21] Shafarik-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#case-mapping">case_mapping</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+03F9: GREEK CAPITAL LUNATE SIGMA SYMBOL</td>
<td align="left">U+03F2: GREEK LUNATE SIGMA SYMBOL</td>
</tr>
<tr>
<td align="left">U+03FD: GREEK CAPITAL REVERSED LUNATE SIGMA SYMBOL</td>
<td align="left">U+037B: GREEK SMALL REVERSED LUNATE SIGMA SYMBOL</td>
</tr>
<tr>
<td align="left">U+03FE: GREEK CAPITAL DOTTED LUNATE SIGMA SYMBOL</td>
<td align="left">U+037C: GREEK SMALL DOTTED LUNATE SIGMA SYMBOL</td>
</tr>
<tr>
<td align="left">U+03FF: GREEK CAPITAL REVERSED DOTTED LUNATE SIGMA SYMBOL</td>
<td align="left">U+037D: GREEK SMALL REVERSED DOTTED LUNATE SIGMA SYMBOL</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.13.1, while a newer 0.13.2 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Shaper didn't attach acutecomb to w</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to W</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to W</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to y</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to w</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to W</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to w</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Y</td>
<td align="left">cy_Latn (Welsh)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: ẞ</td>
<td align="left">de_Latn (German)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to j</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to J</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0326 to S</td>
<td align="left">ro_Latn (Romanian)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0326 to s</td>
<td align="left">ro_Latn (Romanian)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0326 to T</td>
<td align="left">ro_Latn (Romanian)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0326 to t</td>
<td align="left">ro_Latn (Romanian)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ʒ, Ǥ, ǥ, Ǯ, ǯ, ʒ, ẞ</td>
<td align="left">fi_Latn (Finnish)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: ẞ</td>
<td align="left">fr_Latn (French), it_Latn (Italian), pl_Latn (Polish) and tr_Latn (Turkish)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x02C7 (CARON)


- 0x02D8 (BREVE)


- 0x02D9 (DOT ABOVE)


- 0x02DB (OGONEK)


- 0x02DD (DOUBLE ACUTE ACCENT)


- 0x1E80 (LATIN CAPITAL LETTER W WITH GRAVE)


- 0x1E81 (LATIN SMALL LETTER W WITH GRAVE)


- 0x1E82 (LATIN CAPITAL LETTER W WITH ACUTE)


- 0x1E83 (LATIN SMALL LETTER W WITH ACUTE)


- 0x1E84 (LATIN CAPITAL LETTER W WITH DIAERESIS)


- 0x1E85 (LATIN SMALL LETTER W WITH DIAERESIS)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)


- 0x1EF2 (LATIN CAPITAL LETTER Y WITH GRAVE)


- 0x1EF3 (LATIN SMALL LETTER Y WITH GRAVE)


- 0x2122 (TRADE MARK SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni034F (U+034F)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check glyphs in mark glyph class are non-spacing. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-spacing-marks">opentype/gdef_spacing_marks</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs seem to be spacing (because they have width &gt; 0 on the hmtx table) so they may be in the GDEF mark glyph class by mistake, or they should have zero width instead:
acutecomb (U+0301), dotbelowcomb (U+0323), gravecomb (U+0300), u1E000 (U+1E000), u1E001 (U+1E001), u1E002 (U+1E002), u1E003 (U+1E003), u1E004 (U+1E004), u1E005 (U+1E005), u1E006 (U+1E006), u1E007 (U+1E007), u1E008 (U+1E008), u1E009 (U+1E009), u1E00A (U+1E00A), u1E00B (U+1E00B), u1E00C (U+1E00C), u1E00D (U+1E00D), u1E00E (U+1E00E), u1E00F (U+1E00F), u1E010 (U+1E010), u1E011 (U+1E011), u1E012 (U+1E012), u1E013 (U+1E013), u1E014 (U+1E014), u1E015 (U+1E015), u1E015.ss03 (U+F0260), u1E015.ss04 (U+F02D0), u1E016 (U+1E016), u1E017 (U+1E017), u1E018 (U+1E018), u1E019 (U+1E019), u1E01A (U+1E01A), u1E01B (U+1E01B), u1E01C (U+1E01C), u1E01D (U+1E01D), u1E01E (U+1E01E), u1E01F (U+1E01F), u1E020 (U+1E020), u1E021 (U+1E021), u1E022 (U+1E022), u1E023 (U+1E023), u1E024 (U+1E024), u1E025 (U+1E025), u1E026 (U+1E026), u1E027 (U+1E027), u1E028 (U+1E028), u1E029 (U+1E029), u1E02A (U+1E02A), uF0023 (U+F0023), uF0097 (U+F0097), uF0098 (U+F0098), uni0302 (U+0302), uni0303 (U+0303), uni0303.salt5 (U+E011), uni0303.salt6 (U+E012), uni0303.salt7 (U+E013), uni0303.salt8 (U+E014), uni0304 (U+0304), uni0305 (U+0305), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C), uni030F (U+030F), uni0311 (U+0311), uni0312 (U+0312), uni0313 (U+0313), uni0314 (U+0314), uni0326 (U+0326), uni0327 (U+0327), uni0328 (U+0328), uni032E (U+032E), uni032F (U+032F), uni0332 (U+0332), uni033E (U+033E), uni033F (U+033F), uni0350 (U+0350), uni0358 (U+0358), uni035B (U+035B), uni0360 (U+0360), uni0360.salt (U+E015), uni0361 (U+0361), uni0483.salt1 (U+E016), uni0483.salt2 (U+E017), uni0483.salt3 (U+E018), uni0483.salt4 (U+E019), uni0483.salt5 (U+E01A), uni0483.salt6 (U+E01B), uni0483.salt7 (U+E01C), uni0484 (U+0484), uni0485 (U+0485), uni0486 (U+0486), uni0487.salt1 (U+E01D), uni0487.salt2 (U+E01E), uni0488 (U+0488), uni0489 (U+0489), uni1DC0 (U+1DC0), uni1DC1 (U+1DC1), uni1DF8 (U+1DF8), uni1DF9 (U+1DF9), uni20DD (U+20DD), uni2DE0 (U+2DE0), uni2DE1 (U+2DE1), uni2DE2 (U+2DE2), uni2DE3 (U+2DE3), uni2DE4 (U+2DE4), uni2DE5 (U+2DE5), uni2DE6 (U+2DE6), uni2DE7 (U+2DE7), uni2DE8 (U+2DE8), uni2DE9 (U+2DE9), uni2DEA (U+2DEA), uni2DEB (U+2DEB), uni2DEC (U+2DEC), uni2DED (U+2DED), uni2DEE (U+2DEE), uni2DEF (U+2DEF), uni2DF0 (U+2DF0), uni2DF1 (U+2DF1), uni2DF2 (U+2DF2), uni2DF3 (U+2DF3), uni2DF4 (U+2DF4), uni2DF5 (U+2DF5), uni2DF6 (U+2DF6), uni2DF7 (U+2DF7), uni2DF8 (U+2DF8), uni2DF9 (U+2DF9), uni2DFA (U+2DFA), uni2DFB (U+2DFB), uni2DFC (U+2DFC), uni2DFD (U+2DFD), uni2DFE (U+2DFE), uni2DFF (U+2DFF), uniA66F.salt1 (U+E01F), uniA670 (U+A670), uniA671 (U+A671), uniA672 (U+A672), uniA674 (U+A674), uniA675 (U+A675), uniA676 (U+A676), uniA677 (U+A677), uniA678 (U+A678), uniA679 (U+A679), uniA67A (U+A67A), uniA67B (U+A67B), uniA69E (U+A69E), uniA69F (U+A69F), uniE000 (U+E000), uniE001 (U+E001), uniE002 (U+E002), uniE003 (U+E003), uniE004 (U+E004), uniE005 (U+E005), uniE055 (U+E055), uniE056 (U+E056), uniE057 (U+E057), uniE07E (U+E07E), uniE094 (U+E094), uniE098 (U+E098), uniE0B1 (U+E0B1), uniE0B3 (U+E0B3), uniE0B4 (U+E0B4), uniE0BA (U+E0BA), uniE0BB (U+E0BB), uniE0BC (U+E0BC), uniE0BD (U+E0BD), uniEC9C (U+EC9C), uniEC9D (U+EC9D), uniEC9E (U+EC9E), uniEC9F (U+EC9F), uniED60 (U+ED60), uniED70 (U+ED70), uniED80 (U+ED80), uniED90 (U+ED90), uniEDA0 (U+EDA0), uniEDB0 (U+EDB0), uniEDC0 (U+EDC0), uniEDD0 (U+EDD0), uniEDE0 (U+EDE0), uniEDF0 (U+EDF0), uniF4E0 (U+F4E0), uniF4E1 (U+F4E1), uniF4E2 (U+F4E2), uniF4E3 (U+F4E3), uniF4E4 (U+F4E4), uniF4E5 (U+F4E5), uniF4E6 (U+F4E6), uniF4E7 (U+F4E7), uniF4E8 (U+F4E8), uniF4E9 (U+F4E9), uniF4EA (U+F4EA), uniF4EB (U+F4EB), uniF4EC (U+F4EC), uniF4ED (U+F4ED), uniF4EE (U+F4EE), uniF4EF (U+F4EF), uniF4F0 (U+F4F0), uniF4F1 (U+F4F1), uniF4F2 (U+F4F2), uniF4F3 (U+F4F3), uniF4F4 (U+F4F4), uniF4F5 (U+F4F5), uniF4F6 (U+F4F6), uniF4F7 (U+F4F7), uniF4F8 (U+F4F8), uniF4F9 (U+F4F9), uniF4FA (U+F4FA), uniF4FB (U+F4FB), uniF4FC (U+F4FC), uniF4FD (U+F4FD), uniF4FE (U+F4FE), uniF4FF (U+F4FF), uniF674 (U+F674), uniF675 (U+F675), uniF676 (U+F676), uniF677 (U+F677), uniF678 (U+F678), uniF679 (U+F679), uniF67A (U+F67A), uniF67B (U+F67B), uniF69E (U+F69E), uniF69F (U+F69F), uniFE26 (U+FE26), uniFE2E (U+FE2E) and uniFE2F (U+FE2F)</p>
 [code: spacing-mark-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#alt-caron">alt_caron</a></summary>
    <div>









* ⚠️ **WARN** <p>Lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni0000	Contours detected: 5	Expected: 0

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: afii10070	Contours detected: 1	Expected: 2

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: afii10071	Contours detected: 3	Expected: 4

- Glyph name: afii10103	Contours detected: 1	Expected: 2

- Glyph name: afii10105	Contours detected: 1	Expected: 2

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

- Glyph name: uni0450	Contours detected: 2	Expected: 3

- Glyph name: uni046E	Contours detected: 1	Expected: 2

- Glyph name: uni046F	Contours detected: 1	Expected: 2

- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#file-size">file_size</a></summary>
    <div>







* ⚠️ **WARN** <p>Font file is 1.0Mb; ideally it should be less than 1.0Mb</p>
 [code: large-font]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#gpos-kerning-info">gpos_kerning_info</a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 579 among a set of 4 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 561:
plus</p>
<p>Width = 552:
less, greater</p>
<p>Width = 593:
equal</p>
<p>Width = 457:
minus</p>
<p>Width = 887:
similar, uni2241, uni223B, uni223D</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni2C22.ss03.salt (U+EC89): B&lt;&lt;668.0,63.0&gt;-&lt;668.0,63.0&gt;-&lt;668.0,63.0&gt;&gt; has the same coordinates as a previous segment.

* uni2C2F.ss04 (U+F029F): B&lt;&lt;340.0,47.0&gt;-&lt;340.0,47.0&gt;-&lt;340.0,47.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure Stylistic Sets have description. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#stylisticset-description">stylisticset_description</a></summary>
    <div>







* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss01 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss02 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss02 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss03 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss04 lacks a description string on the 'name' table.</p>
 [code: missing-description]



* ⚠️ **WARN** <p>The stylistic set ss05 lacks a description string on the 'name' table.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+007F : try adding symbols</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, math, tai-le, tifinagh, coptic, malayalam, duployan, old-permic, hebrew, syriac, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: todhri, old-permic</li>
<li>U+0314 COMBINING REVERSED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0332 COMBINING LOW LINE: try adding math</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+033F COMBINING DOUBLE OVERLINE: try adding coptic</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0350 COMBINING RIGHT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+035B COMBINING ZIGZAG ABOVE: not included in any glyphset definition</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+03F9 GREEK CAPITAL LUNATE SIGMA SYMBOL: try adding greek</li>
<li>U+03FD GREEK CAPITAL REVERSED LUNATE SIGMA SYMBOL: try adding greek</li>
<li>U+03FE GREEK CAPITAL DOTTED LUNATE SIGMA SYMBOL: try adding greek</li>
<li>U+03FF GREEK CAPITAL REVERSED DOTTED LUNATE SIGMA SYMBOL: try adding greek</li>
<li>U+1DC0 COMBINING DOTTED GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+1DC1 COMBINING DOTTED ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+1DF6 COMBINING KAVYKA ABOVE RIGHT: not included in any glyphset definition</li>
<li>U+1DF7 COMBINING KAVYKA ABOVE LEFT: not included in any glyphset definition</li>
<li>U+1DF8 COMBINING DOT ABOVE LEFT: try adding syriac</li>
<li>U+1DF9 COMBINING WIDE INVERTED BRIDGE BELOW: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: gurmukhi, buhid, cham, oriya, sogdian, avestan, malayalam, grantha, lao, manichaean, nko, tai-le, bhaiksuki, myanmar, masaram-gondi, takri, phags-pa, limbu, tibetan, psalter-pahlavi, gunjala-gondi, pahawh-hmong, mahajani, sundanese, tifinagh, bengali, gujarati, devanagari, arabic, yi, khojki, new-tai-lue, syriac, khmer, warang-citi, syloti-nagri, sinhala, kharoshthi, tamil, lepcha, thaana, tirhuta, hanifi-rohingya, tagbanwa, sharada, siddham, brahmi, kayah-li, tai-tham, hebrew, rejang, balinese, tagalog, mandaic, telugu, thai, chakma, zanabazar-square, hanunoo, khudawadi, modi, newa, dogra, kaithi, duployan, javanese, batak, meetei-mayek, kannada, mongolian, saurashtra, tai-viet, buginese, hatran</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: gurmukhi, buhid, cham, oriya, sogdian, avestan, malayalam, grantha, lao, manichaean, nko, tai-le, bhaiksuki, myanmar, masaram-gondi, takri, phags-pa, limbu, tibetan, psalter-pahlavi, gunjala-gondi, pahawh-hmong, mahajani, sundanese, tifinagh, bengali, gujarati, devanagari, arabic, old-hungarian, khojki, yi, new-tai-lue, syriac, khmer, warang-citi, syloti-nagri, sinhala, kharoshthi, tamil, lepcha, thaana, tirhuta, hanifi-rohingya, tagbanwa, sharada, siddham, brahmi, kayah-li, tai-tham, hebrew, rejang, balinese, tagalog, mandaic, telugu, thai, chakma, zanabazar-square, hanunoo, khudawadi, modi, newa, dogra, kaithi, duployan, javanese, batak, meetei-mayek, kannada, mongolian, saurashtra, tai-viet, buginese</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: thaana, nko, arabic, hebrew, syriac, phags-pa</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: thaana, nko, hebrew, syriac, phags-pa</li>
<li>U+2010 HYPHEN: try adding one of: cham, syloti-nagri, kharoshthi, lisu, sora-sompeng, yi, sundanese, coptic, kaithi, armenian, arabic, kayah-li, hebrew</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: yi, syloti-nagri, arabic</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+201B SINGLE HIGH-REVERSED-9 QUOTATION MARK: try adding adlam</li>
<li>U+201F DOUBLE HIGH-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, mongolian, phags-pa</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+203E OVERLINE: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205B FOUR DOT MARK: not included in any glyphset definition</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: carian, old-hungarian, meroitic, meroitic-hieroglyphs</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+2060 WORD JOINER: not included in any glyphset definition</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+20DD COMBINING ENCLOSING CIRCLE: try adding symbols</li>
<li>U+2219 BULLET OPERATOR: try adding one of: yi, math, symbols, tai-tham</li>
<li>U+223B HOMOTHETIC: try adding math</li>
<li>U+223C TILDE OPERATOR: try adding math</li>
<li>U+223D REVERSED TILDE: try adding math</li>
<li>U+2241 NOT TILDE: try adding math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: gurmukhi, cham, coptic, nko, masaram-gondi, phags-pa, limbu, gujarati, devanagari, yi, tamil, lepcha, marchen, bassa-vah, hanifi-rohingya, brahmi, kayah-li, mende-kikakui, tagalog, wancho, hanunoo, khudawadi, modi, duployan, mongolian, tai-viet, buhid, malayalam, elbasan, bhaiksuki, adlam, miao, tirhuta, tai-tham, old-permic, hebrew, telugu, newa, dogra, kaithi, meetei-mayek, batak, kannada, saurashtra, buginese, osage, grantha, myanmar, psalter-pahlavi, gunjala-gondi, soyombo, pahawh-hmong, tifinagh, bengali, music, armenian, khojki, new-tai-lue, khmer, warang-citi, syloti-nagri, sinhala, kharoshthi, tagbanwa, siddham, rejang, balinese, mandaic, chakma, zanabazar-square, caucasian-albanian, symbols, thai, oriya, math, sogdian, lao, tai-le, takri, tibetan, mahajani, sundanese, ahom, syriac, thaana, sharada, javanese, manichaean, canadian-aboriginal</li>
<li>U+261E WHITE RIGHT POINTING INDEX: try adding symbols</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+263D FIRST QUARTER MOON: try adding symbols</li>
<li>U+263E LAST QUARTER MOON: try adding symbols</li>
<li>U+271A HEAVY GREEK CROSS: try adding symbols</li>
<li>U+2720 MALTESE CROSS: try adding symbols</li>
<li>U+2734 EIGHT POINTED BLACK STAR: try adding symbols</li>
<li>U+29BF CIRCLED BULLET: try adding one of: math, symbols</li>
<li>U+29DF DOUBLE-ENDED MULTIMAP: try adding math</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E45 INVERTED LOW KAVYKA: not included in any glyphset definition</li>
<li>U+2E46 INVERTED LOW KAVYKA WITH KAVYKA ABOVE: not included in any glyphset definition</li>
<li>U+2E47 LOW KAVYKA: not included in any glyphset definition</li>
<li>U+2E48 LOW KAVYKA WITH DOT: not included in any glyphset definition</li>
<li>U+2E49 DOUBLE STACKED COMMA: not included in any glyphset definition</li>
<li>U+E000 : not included in any glyphset definition</li>
<li>U+E001 : not included in any glyphset definition</li>
<li>U+E002 : not included in any glyphset definition</li>
<li>U+E003 : not included in any glyphset definition</li>
<li>U+E004 : not included in any glyphset definition</li>
<li>U+E005 : not included in any glyphset definition</li>
<li>U+E010 : not included in any glyphset definition</li>
<li>U+E011 : not included in any glyphset definition</li>
<li>U+E012 : not included in any glyphset definition</li>
<li>U+E013 : not included in any glyphset definition</li>
<li>U+E014 : not included in any glyphset definition</li>
<li>U+E015 : not included in any glyphset definition</li>
<li>U+E016 : not included in any glyphset definition</li>
<li>U+E017 : not included in any glyphset definition</li>
<li>U+E018 : not included in any glyphset definition</li>
<li>U+E019 : not included in any glyphset definition</li>
<li>U+E01A : not included in any glyphset definition</li>
<li>U+E01B : not included in any glyphset definition</li>
<li>U+E01C : not included in any glyphset definition</li>
<li>U+E01D : not included in any glyphset definition</li>
<li>U+E01E : not included in any glyphset definition</li>
<li>U+E01F : not included in any glyphset definition</li>
<li>U+E055 : not included in any glyphset definition</li>
<li>U+E056 : not included in any glyphset definition</li>
<li>U+E057 : not included in any glyphset definition</li>
<li>U+E07E : not included in any glyphset definition</li>
<li>U+E094 : not included in any glyphset definition</li>
<li>U+E098 : not included in any glyphset definition</li>
<li>U+E0B1 : not included in any glyphset definition</li>
<li>U+E0B3 : not included in any glyphset definition</li>
<li>U+E0B4 : not included in any glyphset definition</li>
<li>U+E0BA : not included in any glyphset definition</li>
<li>U+E0BB : not included in any glyphset definition</li>
<li>U+E0BC : not included in any glyphset definition</li>
<li>U+E0BD : not included in any glyphset definition</li>
<li>U+E1D6 : not included in any glyphset definition</li>
<li>U+E1D7 : not included in any glyphset definition</li>
<li>U+E200 : not included in any glyphset definition</li>
<li>U+E201 : not included in any glyphset definition</li>
<li>U+E400 : not included in any glyphset definition</li>
<li>U+E401 : not included in any glyphset definition</li>
<li>U+E464 : not included in any glyphset definition</li>
<li>U+E465 : not included in any glyphset definition</li>
<li>U+E4E0 : not included in any glyphset definition</li>
<li>U+E4E1 : not included in any glyphset definition</li>
<li>U+E50A : not included in any glyphset definition</li>
<li>U+E50B : not included in any glyphset definition</li>
<li>U+E5FB : not included in any glyphset definition</li>
<li>U+E70F : not included in any glyphset definition</li>
<li>U+E7F0 : not included in any glyphset definition</li>
<li>U+E811 : not included in any glyphset definition</li>
<li>U+E925 : not included in any glyphset definition</li>
<li>U+E926 : not included in any glyphset definition</li>
<li>U+EC45 : not included in any glyphset definition</li>
<li>U+EC46 : not included in any glyphset definition</li>
<li>U+EC47 : not included in any glyphset definition</li>
<li>U+EC48 : not included in any glyphset definition</li>
<li>U+EC49 : not included in any glyphset definition</li>
<li>U+EC50 : not included in any glyphset definition</li>
<li>U+EC60 : not included in any glyphset definition</li>
<li>U+EC61 : not included in any glyphset definition</li>
<li>U+EC62 : not included in any glyphset definition</li>
<li>U+EC63 : not included in any glyphset definition</li>
<li>U+EC64 : not included in any glyphset definition</li>
<li>U+EC65 : not included in any glyphset definition</li>
<li>U+EC66 : not included in any glyphset definition</li>
<li>U+EC67 : not included in any glyphset definition</li>
<li>U+EC68 : not included in any glyphset definition</li>
<li>U+EC69 : not included in any glyphset definition</li>
<li>U+EC6A : not included in any glyphset definition</li>
<li>U+EC6B : not included in any glyphset definition</li>
<li>U+EC6C : not included in any glyphset definition</li>
<li>U+EC6D : not included in any glyphset definition</li>
<li>U+EC6E : not included in any glyphset definition</li>
<li>U+EC6F : not included in any glyphset definition</li>
<li>U+EC76 : not included in any glyphset definition</li>
<li>U+EC77 : not included in any glyphset definition</li>
<li>U+EC78 : not included in any glyphset definition</li>
<li>U+EC79 : not included in any glyphset definition</li>
<li>U+EC7A : not included in any glyphset definition</li>
<li>U+EC7B : not included in any glyphset definition</li>
<li>U+EC7C : not included in any glyphset definition</li>
<li>U+EC7D : not included in any glyphset definition</li>
<li>U+EC7E : not included in any glyphset definition</li>
<li>U+EC7F : not included in any glyphset definition</li>
<li>U+EC80 : not included in any glyphset definition</li>
<li>U+EC81 : not included in any glyphset definition</li>
<li>U+EC82 : not included in any glyphset definition</li>
<li>U+EC83 : not included in any glyphset definition</li>
<li>U+EC84 : not included in any glyphset definition</li>
<li>U+EC85 : not included in any glyphset definition</li>
<li>U+EC86 : not included in any glyphset definition</li>
<li>U+EC87 : not included in any glyphset definition</li>
<li>U+EC88 : not included in any glyphset definition</li>
<li>U+EC89 : not included in any glyphset definition</li>
<li>U+EC8A : not included in any glyphset definition</li>
<li>U+EC8B : not included in any glyphset definition</li>
<li>U+EC8C : not included in any glyphset definition</li>
<li>U+EC8D : not included in any glyphset definition</li>
<li>U+EC8E : not included in any glyphset definition</li>
<li>U+EC8F : not included in any glyphset definition</li>
<li>U+EC90 : not included in any glyphset definition</li>
<li>U+EC91 : not included in any glyphset definition</li>
<li>U+EC9C : not included in any glyphset definition</li>
<li>U+EC9D : not included in any glyphset definition</li>
<li>U+EC9E : not included in any glyphset definition</li>
<li>U+EC9F : not included in any glyphset definition</li>
<li>U+ECA0 : not included in any glyphset definition</li>
<li>U+ECA1 : not included in any glyphset definition</li>
<li>U+ECA2 : not included in any glyphset definition</li>
<li>U+ECA3 : not included in any glyphset definition</li>
<li>U+ECA4 : not included in any glyphset definition</li>
<li>U+ECA5 : not included in any glyphset definition</li>
<li>U+ECA6 : not included in any glyphset definition</li>
<li>U+ECA7 : not included in any glyphset definition</li>
<li>U+ECA8 : not included in any glyphset definition</li>
<li>U+ECA9 : not included in any glyphset definition</li>
<li>U+ECAA : not included in any glyphset definition</li>
<li>U+ECAB : not included in any glyphset definition</li>
<li>U+ECAC : not included in any glyphset definition</li>
<li>U+ECAD : not included in any glyphset definition</li>
<li>U+ECAE : not included in any glyphset definition</li>
<li>U+ECAF : not included in any glyphset definition</li>
<li>U+ECB0 : not included in any glyphset definition</li>
<li>U+ECB1 : not included in any glyphset definition</li>
<li>U+ECB2 : not included in any glyphset definition</li>
<li>U+ECC0 : not included in any glyphset definition</li>
<li>U+ECC1 : not included in any glyphset definition</li>
<li>U+ECC2 : not included in any glyphset definition</li>
<li>U+ECC3 : not included in any glyphset definition</li>
<li>U+ECC4 : not included in any glyphset definition</li>
<li>U+ECC5 : not included in any glyphset definition</li>
<li>U+ECC6 : not included in any glyphset definition</li>
<li>U+ECC7 : not included in any glyphset definition</li>
<li>U+ECC8 : not included in any glyphset definition</li>
<li>U+ECC9 : not included in any glyphset definition</li>
<li>U+ECCA : not included in any glyphset definition</li>
<li>U+ECE0 : not included in any glyphset definition</li>
<li>U+ECE1 : not included in any glyphset definition</li>
<li>U+ECE2 : not included in any glyphset definition</li>
<li>U+ECE3 : not included in any glyphset definition</li>
<li>U+ECE4 : not included in any glyphset definition</li>
<li>U+ECE5 : not included in any glyphset definition</li>
<li>U+ECE6 : not included in any glyphset definition</li>
<li>U+ECE7 : not included in any glyphset definition</li>
<li>U+ECE8 : not included in any glyphset definition</li>
<li>U+ECE9 : not included in any glyphset definition</li>
<li>U+ED00 : not included in any glyphset definition</li>
<li>U+ED01 : not included in any glyphset definition</li>
<li>U+ED02 : not included in any glyphset definition</li>
<li>U+ED03 : not included in any glyphset definition</li>
<li>U+ED04 : not included in any glyphset definition</li>
<li>U+ED05 : not included in any glyphset definition</li>
<li>U+ED06 : not included in any glyphset definition</li>
<li>U+ED07 : not included in any glyphset definition</li>
<li>U+ED08 : not included in any glyphset definition</li>
<li>U+ED09 : not included in any glyphset definition</li>
<li>U+ED0A : not included in any glyphset definition</li>
<li>U+ED0B : not included in any glyphset definition</li>
<li>U+ED0C : not included in any glyphset definition</li>
<li>U+ED0D : not included in any glyphset definition</li>
<li>U+ED0E : not included in any glyphset definition</li>
<li>U+ED0F : not included in any glyphset definition</li>
<li>U+ED10 : not included in any glyphset definition</li>
<li>U+ED11 : not included in any glyphset definition</li>
<li>U+ED12 : not included in any glyphset definition</li>
<li>U+ED13 : not included in any glyphset definition</li>
<li>U+ED14 : not included in any glyphset definition</li>
<li>U+ED15 : not included in any glyphset definition</li>
<li>U+ED16 : not included in any glyphset definition</li>
<li>U+ED17 : not included in any glyphset definition</li>
<li>U+ED18 : not included in any glyphset definition</li>
<li>U+ED19 : not included in any glyphset definition</li>
<li>U+ED1A : not included in any glyphset definition</li>
<li>U+ED1B : not included in any glyphset definition</li>
<li>U+ED1C : not included in any glyphset definition</li>
<li>U+ED1D : not included in any glyphset definition</li>
<li>U+ED1E : not included in any glyphset definition</li>
<li>U+ED1F : not included in any glyphset definition</li>
<li>U+ED20 : not included in any glyphset definition</li>
<li>U+ED21 : not included in any glyphset definition</li>
<li>U+ED22 : not included in any glyphset definition</li>
<li>U+ED23 : not included in any glyphset definition</li>
<li>U+ED24 : not included in any glyphset definition</li>
<li>U+ED25 : not included in any glyphset definition</li>
<li>U+ED26 : not included in any glyphset definition</li>
<li>U+ED27 : not included in any glyphset definition</li>
<li>U+ED28 : not included in any glyphset definition</li>
<li>U+ED29 : not included in any glyphset definition</li>
<li>U+ED2A : not included in any glyphset definition</li>
<li>U+ED2B : not included in any glyphset definition</li>
<li>U+ED2C : not included in any glyphset definition</li>
<li>U+ED2D : not included in any glyphset definition</li>
<li>U+ED2E : not included in any glyphset definition</li>
<li>U+ED2F : not included in any glyphset definition</li>
<li>U+ED30 : not included in any glyphset definition</li>
<li>U+ED31 : not included in any glyphset definition</li>
<li>U+ED32 : not included in any glyphset definition</li>
<li>U+ED33 : not included in any glyphset definition</li>
<li>U+ED34 : not included in any glyphset definition</li>
<li>U+ED35 : not included in any glyphset definition</li>
<li>U+ED36 : not included in any glyphset definition</li>
<li>U+ED37 : not included in any glyphset definition</li>
<li>U+ED38 : not included in any glyphset definition</li>
<li>U+ED39 : not included in any glyphset definition</li>
<li>U+ED3A : not included in any glyphset definition</li>
<li>U+ED3B : not included in any glyphset definition</li>
<li>U+ED3C : not included in any glyphset definition</li>
<li>U+ED3D : not included in any glyphset definition</li>
<li>U+ED3E : not included in any glyphset definition</li>
<li>U+ED3F : not included in any glyphset definition</li>
<li>U+ED40 : not included in any glyphset definition</li>
<li>U+ED41 : not included in any glyphset definition</li>
<li>U+ED42 : not included in any glyphset definition</li>
<li>U+ED43 : not included in any glyphset definition</li>
<li>U+ED44 : not included in any glyphset definition</li>
<li>U+ED45 : not included in any glyphset definition</li>
<li>U+ED46 : not included in any glyphset definition</li>
<li>U+ED47 : not included in any glyphset definition</li>
<li>U+ED48 : not included in any glyphset definition</li>
<li>U+ED49 : not included in any glyphset definition</li>
<li>U+ED4A : not included in any glyphset definition</li>
<li>U+ED4B : not included in any glyphset definition</li>
<li>U+ED4C : not included in any glyphset definition</li>
<li>U+ED4D : not included in any glyphset definition</li>
<li>U+ED4E : not included in any glyphset definition</li>
<li>U+ED4F : not included in any glyphset definition</li>
<li>U+ED50 : not included in any glyphset definition</li>
<li>U+ED51 : not included in any glyphset definition</li>
<li>U+ED52 : not included in any glyphset definition</li>
<li>U+ED53 : not included in any glyphset definition</li>
<li>U+ED54 : not included in any glyphset definition</li>
<li>U+ED55 : not included in any glyphset definition</li>
<li>U+ED56 : not included in any glyphset definition</li>
<li>U+ED57 : not included in any glyphset definition</li>
<li>U+ED58 : not included in any glyphset definition</li>
<li>U+ED59 : not included in any glyphset definition</li>
<li>U+ED5A : not included in any glyphset definition</li>
<li>U+ED5B : not included in any glyphset definition</li>
<li>U+ED5C : not included in any glyphset definition</li>
<li>U+ED5D : not included in any glyphset definition</li>
<li>U+ED5E : not included in any glyphset definition</li>
<li>U+ED5F : not included in any glyphset definition</li>
<li>U+ED60 : not included in any glyphset definition</li>
<li>U+ED61 : not included in any glyphset definition</li>
<li>U+ED62 : not included in any glyphset definition</li>
<li>U+ED63 : not included in any glyphset definition</li>
<li>U+ED64 : not included in any glyphset definition</li>
<li>U+ED65 : not included in any glyphset definition</li>
<li>U+ED66 : not included in any glyphset definition</li>
<li>U+ED67 : not included in any glyphset definition</li>
<li>U+ED68 : not included in any glyphset definition</li>
<li>U+ED69 : not included in any glyphset definition</li>
<li>U+ED6A : not included in any glyphset definition</li>
<li>U+ED6B : not included in any glyphset definition</li>
<li>U+ED6C : not included in any glyphset definition</li>
<li>U+ED6D : not included in any glyphset definition</li>
<li>U+ED6E : not included in any glyphset definition</li>
<li>U+ED6F : not included in any glyphset definition</li>
<li>U+ED70 : not included in any glyphset definition</li>
<li>U+ED71 : not included in any glyphset definition</li>
<li>U+ED72 : not included in any glyphset definition</li>
<li>U+ED73 : not included in any glyphset definition</li>
<li>U+ED74 : not included in any glyphset definition</li>
<li>U+ED75 : not included in any glyphset definition</li>
<li>U+ED76 : not included in any glyphset definition</li>
<li>U+ED77 : not included in any glyphset definition</li>
<li>U+ED78 : not included in any glyphset definition</li>
<li>U+ED79 : not included in any glyphset definition</li>
<li>U+ED7A : not included in any glyphset definition</li>
<li>U+ED7B : not included in any glyphset definition</li>
<li>U+ED7C : not included in any glyphset definition</li>
<li>U+ED7D : not included in any glyphset definition</li>
<li>U+ED7E : not included in any glyphset definition</li>
<li>U+ED7F : not included in any glyphset definition</li>
<li>U+ED80 : not included in any glyphset definition</li>
<li>U+ED81 : not included in any glyphset definition</li>
<li>U+ED82 : not included in any glyphset definition</li>
<li>U+ED83 : not included in any glyphset definition</li>
<li>U+ED84 : not included in any glyphset definition</li>
<li>U+ED85 : not included in any glyphset definition</li>
<li>U+ED86 : not included in any glyphset definition</li>
<li>U+ED87 : not included in any glyphset definition</li>
<li>U+ED88 : not included in any glyphset definition</li>
<li>U+ED89 : not included in any glyphset definition</li>
<li>U+ED8A : not included in any glyphset definition</li>
<li>U+ED8B : not included in any glyphset definition</li>
<li>U+ED8C : not included in any glyphset definition</li>
<li>U+ED8D : not included in any glyphset definition</li>
<li>U+ED8E : not included in any glyphset definition</li>
<li>U+ED8F : not included in any glyphset definition</li>
<li>U+ED90 : not included in any glyphset definition</li>
<li>U+ED91 : not included in any glyphset definition</li>
<li>U+ED92 : not included in any glyphset definition</li>
<li>U+ED93 : not included in any glyphset definition</li>
<li>U+ED94 : not included in any glyphset definition</li>
<li>U+ED95 : not included in any glyphset definition</li>
<li>U+ED96 : not included in any glyphset definition</li>
<li>U+ED97 : not included in any glyphset definition</li>
<li>U+ED98 : not included in any glyphset definition</li>
<li>U+ED99 : not included in any glyphset definition</li>
<li>U+ED9A : not included in any glyphset definition</li>
<li>U+ED9B : not included in any glyphset definition</li>
<li>U+ED9C : not included in any glyphset definition</li>
<li>U+ED9D : not included in any glyphset definition</li>
<li>U+ED9E : not included in any glyphset definition</li>
<li>U+ED9F : not included in any glyphset definition</li>
<li>U+EDA0 : not included in any glyphset definition</li>
<li>U+EDA1 : not included in any glyphset definition</li>
<li>U+EDA2 : not included in any glyphset definition</li>
<li>U+EDA3 : not included in any glyphset definition</li>
<li>U+EDA4 : not included in any glyphset definition</li>
<li>U+EDA5 : not included in any glyphset definition</li>
<li>U+EDA6 : not included in any glyphset definition</li>
<li>U+EDA7 : not included in any glyphset definition</li>
<li>U+EDA8 : not included in any glyphset definition</li>
<li>U+EDA9 : not included in any glyphset definition</li>
<li>U+EDAA : not included in any glyphset definition</li>
<li>U+EDAB : not included in any glyphset definition</li>
<li>U+EDAC : not included in any glyphset definition</li>
<li>U+EDAD : not included in any glyphset definition</li>
<li>U+EDAE : not included in any glyphset definition</li>
<li>U+EDAF : not included in any glyphset definition</li>
<li>U+EDB0 : not included in any glyphset definition</li>
<li>U+EDB1 : not included in any glyphset definition</li>
<li>U+EDB2 : not included in any glyphset definition</li>
<li>U+EDB3 : not included in any glyphset definition</li>
<li>U+EDB4 : not included in any glyphset definition</li>
<li>U+EDB5 : not included in any glyphset definition</li>
<li>U+EDB6 : not included in any glyphset definition</li>
<li>U+EDB7 : not included in any glyphset definition</li>
<li>U+EDB8 : not included in any glyphset definition</li>
<li>U+EDB9 : not included in any glyphset definition</li>
<li>U+EDBA : not included in any glyphset definition</li>
<li>U+EDBB : not included in any glyphset definition</li>
<li>U+EDBC : not included in any glyphset definition</li>
<li>U+EDBD : not included in any glyphset definition</li>
<li>U+EDBE : not included in any glyphset definition</li>
<li>U+EDBF : not included in any glyphset definition</li>
<li>U+EDC0 : not included in any glyphset definition</li>
<li>U+EDC1 : not included in any glyphset definition</li>
<li>U+EDC2 : not included in any glyphset definition</li>
<li>U+EDC3 : not included in any glyphset definition</li>
<li>U+EDC4 : not included in any glyphset definition</li>
<li>U+EDC5 : not included in any glyphset definition</li>
<li>U+EDC6 : not included in any glyphset definition</li>
<li>U+EDC7 : not included in any glyphset definition</li>
<li>U+EDC8 : not included in any glyphset definition</li>
<li>U+EDC9 : not included in any glyphset definition</li>
<li>U+EDCA : not included in any glyphset definition</li>
<li>U+EDCB : not included in any glyphset definition</li>
<li>U+EDCC : not included in any glyphset definition</li>
<li>U+EDCD : not included in any glyphset definition</li>
<li>U+EDCE : not included in any glyphset definition</li>
<li>U+EDCF : not included in any glyphset definition</li>
<li>U+EDD0 : not included in any glyphset definition</li>
<li>U+EDD1 : not included in any glyphset definition</li>
<li>U+EDD2 : not included in any glyphset definition</li>
<li>U+EDD3 : not included in any glyphset definition</li>
<li>U+EDD4 : not included in any glyphset definition</li>
<li>U+EDD5 : not included in any glyphset definition</li>
<li>U+EDD6 : not included in any glyphset definition</li>
<li>U+EDD7 : not included in any glyphset definition</li>
<li>U+EDD8 : not included in any glyphset definition</li>
<li>U+EDD9 : not included in any glyphset definition</li>
<li>U+EDDA : not included in any glyphset definition</li>
<li>U+EDDB : not included in any glyphset definition</li>
<li>U+EDDC : not included in any glyphset definition</li>
<li>U+EDDD : not included in any glyphset definition</li>
<li>U+EDDE : not included in any glyphset definition</li>
<li>U+EDDF : not included in any glyphset definition</li>
<li>U+EDE0 : not included in any glyphset definition</li>
<li>U+EDE1 : not included in any glyphset definition</li>
<li>U+EDE2 : not included in any glyphset definition</li>
<li>U+EDE3 : not included in any glyphset definition</li>
<li>U+EDE4 : not included in any glyphset definition</li>
<li>U+EDE5 : not included in any glyphset definition</li>
<li>U+EDE6 : not included in any glyphset definition</li>
<li>U+EDE7 : not included in any glyphset definition</li>
<li>U+EDE8 : not included in any glyphset definition</li>
<li>U+EDE9 : not included in any glyphset definition</li>
<li>U+EDEA : not included in any glyphset definition</li>
<li>U+EDEB : not included in any glyphset definition</li>
<li>U+EDEC : not included in any glyphset definition</li>
<li>U+EDED : not included in any glyphset definition</li>
<li>U+EDEE : not included in any glyphset definition</li>
<li>U+EDEF : not included in any glyphset definition</li>
<li>U+EDF0 : not included in any glyphset definition</li>
<li>U+EDF1 : not included in any glyphset definition</li>
<li>U+EDF2 : not included in any glyphset definition</li>
<li>U+EDF3 : not included in any glyphset definition</li>
<li>U+EDF4 : not included in any glyphset definition</li>
<li>U+EDF5 : not included in any glyphset definition</li>
<li>U+EDF6 : not included in any glyphset definition</li>
<li>U+EDF7 : not included in any glyphset definition</li>
<li>U+EDF8 : not included in any glyphset definition</li>
<li>U+EDF9 : not included in any glyphset definition</li>
<li>U+EDFA : not included in any glyphset definition</li>
<li>U+EDFB : not included in any glyphset definition</li>
<li>U+EDFC : not included in any glyphset definition</li>
<li>U+EDFD : not included in any glyphset definition</li>
<li>U+EDFE : not included in any glyphset definition</li>
<li>U+EDFF : not included in any glyphset definition</li>
<li>U+F4E0 : not included in any glyphset definition</li>
<li>U+F4E1 : not included in any glyphset definition</li>
<li>U+F4E2 : not included in any glyphset definition</li>
<li>U+F4E3 : not included in any glyphset definition</li>
<li>U+F4E4 : not included in any glyphset definition</li>
<li>U+F4E5 : not included in any glyphset definition</li>
<li>U+F4E6 : not included in any glyphset definition</li>
<li>U+F4E7 : not included in any glyphset definition</li>
<li>U+F4E8 : not included in any glyphset definition</li>
<li>U+F4E9 : not included in any glyphset definition</li>
<li>U+F4EA : not included in any glyphset definition</li>
<li>U+F4EB : not included in any glyphset definition</li>
<li>U+F4EC : not included in any glyphset definition</li>
<li>U+F4ED : not included in any glyphset definition</li>
<li>U+F4EE : not included in any glyphset definition</li>
<li>U+F4EF : not included in any glyphset definition</li>
<li>U+F4F0 : not included in any glyphset definition</li>
<li>U+F4F1 : not included in any glyphset definition</li>
<li>U+F4F2 : not included in any glyphset definition</li>
<li>U+F4F3 : not included in any glyphset definition</li>
<li>U+F4F4 : not included in any glyphset definition</li>
<li>U+F4F5 : not included in any glyphset definition</li>
<li>U+F4F6 : not included in any glyphset definition</li>
<li>U+F4F7 : not included in any glyphset definition</li>
<li>U+F4F8 : not included in any glyphset definition</li>
<li>U+F4F9 : not included in any glyphset definition</li>
<li>U+F4FA : not included in any glyphset definition</li>
<li>U+F4FB : not included in any glyphset definition</li>
<li>U+F4FC : not included in any glyphset definition</li>
<li>U+F4FD : not included in any glyphset definition</li>
<li>U+F4FE : not included in any glyphset definition</li>
<li>U+F4FF : not included in any glyphset definition</li>
<li>U+F674 : not included in any glyphset definition</li>
<li>U+F675 : not included in any glyphset definition</li>
<li>U+F676 : not included in any glyphset definition</li>
<li>U+F677 : not included in any glyphset definition</li>
<li>U+F678 : not included in any glyphset definition</li>
<li>U+F679 : not included in any glyphset definition</li>
<li>U+F67A : not included in any glyphset definition</li>
<li>U+F67B : not included in any glyphset definition</li>
<li>U+F69E : not included in any glyphset definition</li>
<li>U+F69F : not included in any glyphset definition</li>
<li>U+F6A0 : not included in any glyphset definition</li>
<li>U+FE26 COMBINING CONJOINING MACRON: try adding one of: caucasian-albanian, coptic</li>
<li>U+1D000 BYZANTINE MUSICAL SYMBOL PSILI: try adding music</li>
<li>U+1D001 BYZANTINE MUSICAL SYMBOL DASEIA: try adding music</li>
<li>U+1D002 BYZANTINE MUSICAL SYMBOL PERISPOMENI: try adding music</li>
<li>U+1D003 BYZANTINE MUSICAL SYMBOL OXEIA EKFONITIKON: try adding music</li>
<li>U+1D004 BYZANTINE MUSICAL SYMBOL OXEIA DIPLI: try adding music</li>
<li>U+1D005 BYZANTINE MUSICAL SYMBOL VAREIA EKFONITIKON: try adding music</li>
<li>U+1D006 BYZANTINE MUSICAL SYMBOL VAREIA DIPLI: try adding music</li>
<li>U+1D007 BYZANTINE MUSICAL SYMBOL KATHISTI: try adding music</li>
<li>U+1D008 BYZANTINE MUSICAL SYMBOL SYRMATIKI: try adding music</li>
<li>U+1D009 BYZANTINE MUSICAL SYMBOL PARAKLITIKI: try adding music</li>
<li>U+1D00A BYZANTINE MUSICAL SYMBOL YPOKRISIS: try adding music</li>
<li>U+1D00B BYZANTINE MUSICAL SYMBOL YPOKRISIS DIPLI: try adding music</li>
<li>U+1D00C BYZANTINE MUSICAL SYMBOL KREMASTI: try adding music</li>
<li>U+1D00D BYZANTINE MUSICAL SYMBOL APESO EKFONITIKON: try adding music</li>
<li>U+1D00E BYZANTINE MUSICAL SYMBOL EXO EKFONITIKON: try adding music</li>
<li>U+1D00F BYZANTINE MUSICAL SYMBOL TELEIA: try adding music</li>
<li>U+1D010 BYZANTINE MUSICAL SYMBOL KENTIMATA: try adding music</li>
<li>U+1D011 BYZANTINE MUSICAL SYMBOL APOSTROFOS: try adding music</li>
<li>U+1D012 BYZANTINE MUSICAL SYMBOL APOSTROFOS DIPLI: try adding music</li>
<li>U+1D013 BYZANTINE MUSICAL SYMBOL SYNEVMA: try adding music</li>
<li>U+1D014 BYZANTINE MUSICAL SYMBOL THITA: try adding music</li>
<li>U+1E007 : not included in any glyphset definition</li>
<li>U+1E019 : not included in any glyphset definition</li>
<li>U+1E01A : not included in any glyphset definition</li>
<li>U+1E022 : not included in any glyphset definition</li>
<li>U+1E025 : not included in any glyphset definition</li>
<li>U+1F311 NEW MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F312 WAXING CRESCENT MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F313 FIRST QUARTER MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F314 WAXING GIBBOUS MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F315 FULL MOON SYMBOL: try adding symbols</li>
<li>U+1F316 WANING GIBBOUS MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F317 LAST QUARTER MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F318 WANING CRESCENT MOON SYMBOL: not included in any glyphset definition</li>
<li>U+1F319 CRESCENT MOON: not included in any glyphset definition</li>
<li>U+1F347 GRAPES: not included in any glyphset definition</li>
<li>U+1F377 WINE GLASS: not included in any glyphset definition</li>
<li>U+1F41F FISH: try adding symbols</li>
<li>U+1F540 CIRCLED CROSS POMMEE: try adding symbols</li>
<li>U+1F541 CROSS POMMEE WITH HALF-CIRCLE BELOW: try adding symbols</li>
<li>U+1F542 CROSS POMMEE: try adding symbols</li>
<li>U+1F543 NOTCHED LEFT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F544 NOTCHED RIGHT SEMICIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F545 SYMBOL FOR MARKS CHAPTER: try adding symbols</li>
<li>U+1F900 CIRCLED CROSS FORMEE WITH FOUR DOTS: try adding symbols</li>
<li>U+1F901 CIRCLED CROSS FORMEE WITH TWO DOTS: try adding symbols</li>
<li>U+1F902 CIRCLED CROSS FORMEE: try adding symbols</li>
<li>U+1F903 LEFT HALF CIRCLE WITH FOUR DOTS: try adding symbols</li>
<li>U+1F904 LEFT HALF CIRCLE WITH THREE DOTS: try adding symbols</li>
<li>U+1F905 LEFT HALF CIRCLE WITH TWO DOTS: try adding symbols</li>
<li>U+1F906 LEFT HALF CIRCLE WITH DOT: try adding symbols</li>
<li>U+1F907 LEFT HALF CIRCLE: try adding symbols</li>
<li>U+1F908 DOWNWARD FACING HOOK: try adding symbols</li>
<li>U+1F909 DOWNWARD FACING NOTCHED HOOK: try adding symbols</li>
<li>U+1F90A DOWNWARD FACING HOOK WITH DOT: try adding symbols</li>
<li>U+1F90B DOWNWARD FACING NOTCHED HOOK WITH DOT: try adding symbols</li>
<li>U+F0023 : not included in any glyphset definition</li>
<li>U+F0097 : not included in any glyphset definition</li>
<li>U+F0098 : not included in any glyphset definition</li>
<li>U+F0111 : not included in any glyphset definition</li>
<li>U+F0134 : not included in any glyphset definition</li>
<li>U+F0135 : not included in any glyphset definition</li>
<li>U+F0136 : not included in any glyphset definition</li>
<li>U+F0137 : not included in any glyphset definition</li>
<li>U+F0138 : not included in any glyphset definition</li>
<li>U+F0139 : not included in any glyphset definition</li>
<li>U+F013A : not included in any glyphset definition</li>
<li>U+F013B : not included in any glyphset definition</li>
<li>U+F0200 : not included in any glyphset definition</li>
<li>U+F0201 : not included in any glyphset definition</li>
<li>U+F0202 : not included in any glyphset definition</li>
<li>U+F0203 : not included in any glyphset definition</li>
<li>U+F0204 : not included in any glyphset definition</li>
<li>U+F0205 : not included in any glyphset definition</li>
<li>U+F0206 : not included in any glyphset definition</li>
<li>U+F0207 : not included in any glyphset definition</li>
<li>U+F0208 : not included in any glyphset definition</li>
<li>U+F0209 : not included in any glyphset definition</li>
<li>U+F020A : not included in any glyphset definition</li>
<li>U+F020B : not included in any glyphset definition</li>
<li>U+F020C : not included in any glyphset definition</li>
<li>U+F020D : not included in any glyphset definition</li>
<li>U+F020E : not included in any glyphset definition</li>
<li>U+F020F : not included in any glyphset definition</li>
<li>U+F0210 : not included in any glyphset definition</li>
<li>U+F0211 : not included in any glyphset definition</li>
<li>U+F0212 : not included in any glyphset definition</li>
<li>U+F0213 : not included in any glyphset definition</li>
<li>U+F0214 : not included in any glyphset definition</li>
<li>U+F0215 : not included in any glyphset definition</li>
<li>U+F0216 : not included in any glyphset definition</li>
<li>U+F0217 : not included in any glyphset definition</li>
<li>U+F0218 : not included in any glyphset definition</li>
<li>U+F0219 : not included in any glyphset definition</li>
<li>U+F021A : not included in any glyphset definition</li>
<li>U+F021B : not included in any glyphset definition</li>
<li>U+F021C : not included in any glyphset definition</li>
<li>U+F021D : not included in any glyphset definition</li>
<li>U+F021E : not included in any glyphset definition</li>
<li>U+F021F : not included in any glyphset definition</li>
<li>U+F0220 : not included in any glyphset definition</li>
<li>U+F0221 : not included in any glyphset definition</li>
<li>U+F0222 : not included in any glyphset definition</li>
<li>U+F0223 : not included in any glyphset definition</li>
<li>U+F0224 : not included in any glyphset definition</li>
<li>U+F0225 : not included in any glyphset definition</li>
<li>U+F0226 : not included in any glyphset definition</li>
<li>U+F0227 : not included in any glyphset definition</li>
<li>U+F0228 : not included in any glyphset definition</li>
<li>U+F0229 : not included in any glyphset definition</li>
<li>U+F022A : not included in any glyphset definition</li>
<li>U+F022B : not included in any glyphset definition</li>
<li>U+F022C : not included in any glyphset definition</li>
<li>U+F022D : not included in any glyphset definition</li>
<li>U+F022E : not included in any glyphset definition</li>
<li>U+F022F : not included in any glyphset definition</li>
<li>U+F0230 : not included in any glyphset definition</li>
<li>U+F0231 : not included in any glyphset definition</li>
<li>U+F0232 : not included in any glyphset definition</li>
<li>U+F0233 : not included in any glyphset definition</li>
<li>U+F0234 : not included in any glyphset definition</li>
<li>U+F0235 : not included in any glyphset definition</li>
<li>U+F0236 : not included in any glyphset definition</li>
<li>U+F0237 : not included in any glyphset definition</li>
<li>U+F0238 : not included in any glyphset definition</li>
<li>U+F0239 : not included in any glyphset definition</li>
<li>U+F023A : not included in any glyphset definition</li>
<li>U+F023B : not included in any glyphset definition</li>
<li>U+F023C : not included in any glyphset definition</li>
<li>U+F023D : not included in any glyphset definition</li>
<li>U+F023E : not included in any glyphset definition</li>
<li>U+F023F : not included in any glyphset definition</li>
<li>U+F0240 : not included in any glyphset definition</li>
<li>U+F0241 : not included in any glyphset definition</li>
<li>U+F0242 : not included in any glyphset definition</li>
<li>U+F0243 : not included in any glyphset definition</li>
<li>U+F0244 : not included in any glyphset definition</li>
<li>U+F0245 : not included in any glyphset definition</li>
<li>U+F0246 : not included in any glyphset definition</li>
<li>U+F0247 : not included in any glyphset definition</li>
<li>U+F0248 : not included in any glyphset definition</li>
<li>U+F0249 : not included in any glyphset definition</li>
<li>U+F024A : not included in any glyphset definition</li>
<li>U+F024B : not included in any glyphset definition</li>
<li>U+F024C : not included in any glyphset definition</li>
<li>U+F024D : not included in any glyphset definition</li>
<li>U+F024E : not included in any glyphset definition</li>
<li>U+F024F : not included in any glyphset definition</li>
<li>U+F0250 : not included in any glyphset definition</li>
<li>U+F0251 : not included in any glyphset definition</li>
<li>U+F0252 : not included in any glyphset definition</li>
<li>U+F0253 : not included in any glyphset definition</li>
<li>U+F0254 : not included in any glyphset definition</li>
<li>U+F0255 : not included in any glyphset definition</li>
<li>U+F0256 : not included in any glyphset definition</li>
<li>U+F0257 : not included in any glyphset definition</li>
<li>U+F0258 : not included in any glyphset definition</li>
<li>U+F0259 : not included in any glyphset definition</li>
<li>U+F025A : not included in any glyphset definition</li>
<li>U+F025B : not included in any glyphset definition</li>
<li>U+F025C : not included in any glyphset definition</li>
<li>U+F025D : not included in any glyphset definition</li>
<li>U+F025E : not included in any glyphset definition</li>
<li>U+F025F : not included in any glyphset definition</li>
<li>U+F0260 : not included in any glyphset definition</li>
<li>U+F0270 : not included in any glyphset definition</li>
<li>U+F0271 : not included in any glyphset definition</li>
<li>U+F0272 : not included in any glyphset definition</li>
<li>U+F0273 : not included in any glyphset definition</li>
<li>U+F0274 : not included in any glyphset definition</li>
<li>U+F0275 : not included in any glyphset definition</li>
<li>U+F0276 : not included in any glyphset definition</li>
<li>U+F0277 : not included in any glyphset definition</li>
<li>U+F0278 : not included in any glyphset definition</li>
<li>U+F0279 : not included in any glyphset definition</li>
<li>U+F027A : not included in any glyphset definition</li>
<li>U+F027B : not included in any glyphset definition</li>
<li>U+F027C : not included in any glyphset definition</li>
<li>U+F027D : not included in any glyphset definition</li>
<li>U+F027E : not included in any glyphset definition</li>
<li>U+F027F : not included in any glyphset definition</li>
<li>U+F0280 : not included in any glyphset definition</li>
<li>U+F0281 : not included in any glyphset definition</li>
<li>U+F0282 : not included in any glyphset definition</li>
<li>U+F0283 : not included in any glyphset definition</li>
<li>U+F0284 : not included in any glyphset definition</li>
<li>U+F0285 : not included in any glyphset definition</li>
<li>U+F0286 : not included in any glyphset definition</li>
<li>U+F0287 : not included in any glyphset definition</li>
<li>U+F0288 : not included in any glyphset definition</li>
<li>U+F0289 : not included in any glyphset definition</li>
<li>U+F028A : not included in any glyphset definition</li>
<li>U+F028B : not included in any glyphset definition</li>
<li>U+F028C : not included in any glyphset definition</li>
<li>U+F028D : not included in any glyphset definition</li>
<li>U+F028E : not included in any glyphset definition</li>
<li>U+F028F : not included in any glyphset definition</li>
<li>U+F0290 : not included in any glyphset definition</li>
<li>U+F0291 : not included in any glyphset definition</li>
<li>U+F0292 : not included in any glyphset definition</li>
<li>U+F0293 : not included in any glyphset definition</li>
<li>U+F0294 : not included in any glyphset definition</li>
<li>U+F0295 : not included in any glyphset definition</li>
<li>U+F0296 : not included in any glyphset definition</li>
<li>U+F0297 : not included in any glyphset definition</li>
<li>U+F0298 : not included in any glyphset definition</li>
<li>U+F0299 : not included in any glyphset definition</li>
<li>U+F029A : not included in any glyphset definition</li>
<li>U+F029B : not included in any glyphset definition</li>
<li>U+F029C : not included in any glyphset definition</li>
<li>U+F029D : not included in any glyphset definition</li>
<li>U+F029E : not included in any glyphset definition</li>
<li>U+F029F : not included in any glyphset definition</li>
<li>U+F02A0 : not included in any glyphset definition</li>
<li>U+F02A1 : not included in any glyphset definition</li>
<li>U+F02A2 : not included in any glyphset definition</li>
<li>U+F02A3 : not included in any glyphset definition</li>
<li>U+F02A4 : not included in any glyphset definition</li>
<li>U+F02A5 : not included in any glyphset definition</li>
<li>U+F02A6 : not included in any glyphset definition</li>
<li>U+F02A7 : not included in any glyphset definition</li>
<li>U+F02A8 : not included in any glyphset definition</li>
<li>U+F02A9 : not included in any glyphset definition</li>
<li>U+F02AA : not included in any glyphset definition</li>
<li>U+F02AB : not included in any glyphset definition</li>
<li>U+F02AC : not included in any glyphset definition</li>
<li>U+F02AD : not included in any glyphset definition</li>
<li>U+F02AE : not included in any glyphset definition</li>
<li>U+F02AF : not included in any glyphset definition</li>
<li>U+F02B0 : not included in any glyphset definition</li>
<li>U+F02B1 : not included in any glyphset definition</li>
<li>U+F02B2 : not included in any glyphset definition</li>
<li>U+F02B3 : not included in any glyphset definition</li>
<li>U+F02B4 : not included in any glyphset definition</li>
<li>U+F02B5 : not included in any glyphset definition</li>
<li>U+F02B6 : not included in any glyphset definition</li>
<li>U+F02B7 : not included in any glyphset definition</li>
<li>U+F02B8 : not included in any glyphset definition</li>
<li>U+F02B9 : not included in any glyphset definition</li>
<li>U+F02BA : not included in any glyphset definition</li>
<li>U+F02BB : not included in any glyphset definition</li>
<li>U+F02BC : not included in any glyphset definition</li>
<li>U+F02BD : not included in any glyphset definition</li>
<li>U+F02BE : not included in any glyphset definition</li>
<li>U+F02BF : not included in any glyphset definition</li>
<li>U+F02C0 : not included in any glyphset definition</li>
<li>U+F02C1 : not included in any glyphset definition</li>
<li>U+F02C2 : not included in any glyphset definition</li>
<li>U+F02C3 : not included in any glyphset definition</li>
<li>U+F02C4 : not included in any glyphset definition</li>
<li>U+F02C5 : not included in any glyphset definition</li>
<li>U+F02C6 : not included in any glyphset definition</li>
<li>U+F02C7 : not included in any glyphset definition</li>
<li>U+F02C8 : not included in any glyphset definition</li>
<li>U+F02C9 : not included in any glyphset definition</li>
<li>U+F02CA : not included in any glyphset definition</li>
<li>U+F02CB : not included in any glyphset definition</li>
<li>U+F02CC : not included in any glyphset definition</li>
<li>U+F02CD : not included in any glyphset definition</li>
<li>U+F02CE : not included in any glyphset definition</li>
<li>U+F02CF : not included in any glyphset definition</li>
<li>U+F02D0 : not included in any glyphset definition</li>
<li>U+F02E0 : not included in any glyphset definition</li>
<li>U+F02E1 : not included in any glyphset definition</li>
<li>U+F02E2 : not included in any glyphset definition</li>
<li>U+F02E3 : not included in any glyphset definition</li>
<li>U+F02E4 : not included in any glyphset definition</li>
<li>U+F02E5 : not included in any glyphset definition</li>
<li>U+F02E7 : not included in any glyphset definition</li>
<li>U+F02E8 : not included in any glyphset definition</li>
<li>U+F02EA : not included in any glyphset definition</li>
<li>U+F02EB : not included in any glyphset definition</li>
<li>U+F02ED : not included in any glyphset definition</li>
<li>U+F02EE : not included in any glyphset definition</li>
<li>U+F02F0 : not included in any glyphset definition</li>
<li>U+F02F1 : not included in any glyphset definition</li>
<li>U+F02F3 : not included in any glyphset definition</li>
<li>U+F02F4 : not included in any glyphset definition</li>
<li>U+F0300 : not included in any glyphset definition</li>
<li>U+F0301 : not included in any glyphset definition</li>
<li>U+F0302 : not included in any glyphset definition</li>
<li>U+F0303 : not included in any glyphset definition</li>
<li>U+F0304 : not included in any glyphset definition</li>
<li>U+F0305 : not included in any glyphset definition</li>
<li>U+F0306 : not included in any glyphset definition</li>
<li>U+F0307 : not included in any glyphset definition</li>
<li>U+F0308 : not included in any glyphset definition</li>
<li>U+F0309 : not included in any glyphset definition</li>
<li>U+F030A : not included in any glyphset definition</li>
<li>U+F030B : not included in any glyphset definition</li>
<li>U+F030C : not included in any glyphset definition</li>
<li>U+F030D : not included in any glyphset definition</li>
<li>U+F030E : not included in any glyphset definition</li>
<li>U+F0315 : not included in any glyphset definition</li>
<li>U+F0316 : not included in any glyphset definition</li>
<li>U+F0317 : not included in any glyphset definition</li>
<li>U+F0318 : not included in any glyphset definition</li>
<li>U+F0319 : not included in any glyphset definition</li>
<li>U+F031A : not included in any glyphset definition</li>
<li>U+F031B : not included in any glyphset definition</li>
<li>U+F031C : not included in any glyphset definition</li>
<li>U+F0323 : not included in any glyphset definition</li>
<li>U+F0324 : not included in any glyphset definition</li>
<li>U+F0325 : not included in any glyphset definition</li>
<li>U+F0326 : not included in any glyphset definition</li>
<li>U+F0327 : not included in any glyphset definition</li>
<li>U+F0328 : not included in any glyphset definition</li>
<li>U+F0329 : not included in any glyphset definition</li>
<li>U+F032A : not included in any glyphset definition</li>
<li>U+F032B : not included in any glyphset definition</li>
<li>U+F032C : not included in any glyphset definition</li>
<li>U+F032D : not included in any glyphset definition</li>
<li>U+F032E : not included in any glyphset definition</li>
<li>U+F032F : not included in any glyphset definition</li>
<li>U+F0330 : not included in any glyphset definition</li>
<li>U+F0331 : not included in any glyphset definition</li>
<li>U+F0332 : not included in any glyphset definition</li>
<li>U+F0333 : not included in any glyphset definition</li>
<li>U+F0334 : not included in any glyphset definition</li>
<li>U+F0335 : not included in any glyphset definition</li>
<li>U+F0336 : not included in any glyphset definition</li>
<li>U+F0337 : not included in any glyphset definition</li>
<li>U+F0338 : not included in any glyphset definition</li>
<li>U+F0339 : not included in any glyphset definition</li>
<li>U+F033A : not included in any glyphset definition</li>
<li>U+F033B : not included in any glyphset definition</li>
<li>U+F033C : not included in any glyphset definition</li>
<li>U+F033D : not included in any glyphset definition</li>
<li>U+F033E : not included in any glyphset definition</li>
<li>U+F033F : not included in any glyphset definition</li>
<li>U+F0346 : not included in any glyphset definition</li>
<li>U+F0347 : not included in any glyphset definition</li>
<li>U+F0348 : not included in any glyphset definition</li>
<li>U+F0349 : not included in any glyphset definition</li>
<li>U+F034A : not included in any glyphset definition</li>
<li>U+F034B : not included in any glyphset definition</li>
<li>U+F034C : not included in any glyphset definition</li>
<li>U+F034D : not included in any glyphset definition</li>
<li>U+F034E : not included in any glyphset definition</li>
<li>U+F034F : not included in any glyphset definition</li>
<li>U+F0350 : not included in any glyphset definition</li>
<li>U+F0351 : not included in any glyphset definition</li>
<li>U+F0352 : not included in any glyphset definition</li>
<li>U+F0353 : not included in any glyphset definition</li>
<li>U+F0354 : not included in any glyphset definition</li>
<li>U+F0355 : not included in any glyphset definition</li>
<li>U+F0356 : not included in any glyphset definition</li>
<li>U+F0357 : not included in any glyphset definition</li>
<li>U+F0358 : not included in any glyphset definition</li>
<li>U+F0359 : not included in any glyphset definition</li>
<li>U+F035A : not included in any glyphset definition</li>
<li>U+F0361 : not included in any glyphset definition</li>
<li>U+F0362 : not included in any glyphset definition</li>
<li>U+F0363 : not included in any glyphset definition</li>
<li>U+F0364 : not included in any glyphset definition</li>
<li>U+F0365 : not included in any glyphset definition</li>
<li>U+F036C : not included in any glyphset definition</li>
<li>U+F036D : not included in any glyphset definition</li>
<li>U+F036E : not included in any glyphset definition</li>
<li>U+F0375 : not included in any glyphset definition</li>
<li>U+F0376 : not included in any glyphset definition</li>
<li>U+F0377 : not included in any glyphset definition</li>
<li>U+F0378 : not included in any glyphset definition</li>
<li>U+F0379 : not included in any glyphset definition</li>
<li>U+F037A : not included in any glyphset definition</li>
<li>U+F037B : not included in any glyphset definition</li>
<li>U+F037C : not included in any glyphset definition</li>
<li>U+F037D : not included in any glyphset definition</li>
<li>U+F037E : not included in any glyphset definition</li>
<li>U+F037F : not included in any glyphset definition</li>
<li>U+F0380 : not included in any glyphset definition</li>
<li>U+F038D : not included in any glyphset definition</li>
<li>U+F038E : not included in any glyphset definition</li>
<li>U+F038F : not included in any glyphset definition</li>
<li>U+F0390 : not included in any glyphset definition</li>
<li>U+F0391 : not included in any glyphset definition</li>
<li>U+F0392 : not included in any glyphset definition</li>
<li>U+F0393 : not included in any glyphset definition</li>
<li>U+F0394 : not included in any glyphset definition</li>
<li>U+F0395 : not included in any glyphset definition</li>
<li>U+F0396 : not included in any glyphset definition</li>
<li>U+F0397 : not included in any glyphset definition</li>
<li>U+F0398 : not included in any glyphset definition</li>
<li>U+F0399 : not included in any glyphset definition</li>
<li>U+F039A : not included in any glyphset definition</li>
<li>U+F039B : not included in any glyphset definition</li>
<li>U+F039C : not included in any glyphset definition</li>
<li>U+F039D : not included in any glyphset definition</li>
<li>U+F039E : not included in any glyphset definition</li>
<li>U+F039F : not included in any glyphset definition</li>
<li>U+F03A0 : not included in any glyphset definition</li>
<li>U+F03A1 : not included in any glyphset definition</li>
<li>U+F03A8 : not included in any glyphset definition</li>
<li>U+F03A9 : not included in any glyphset definition</li>
<li>U+F03AA : not included in any glyphset definition</li>
<li>U+F03AB : not included in any glyphset definition</li>
<li>U+F03AC : not included in any glyphset definition</li>
<li>U+F03B2 : not included in any glyphset definition</li>
<li>U+F03B3 : not included in any glyphset definition</li>
<li>U+F03B4 : not included in any glyphset definition</li>
<li>U+F03B5 : not included in any glyphset definition</li>
<li>U+F03B6 : not included in any glyphset definition</li>
<li>U+F03B7 : not included in any glyphset definition</li>
<li>U+F03B8 : not included in any glyphset definition</li>
<li>U+F03B9 : not included in any glyphset definition</li>
<li>U+F03BA : not included in any glyphset definition</li>
<li>U+F03C1 : not included in any glyphset definition</li>
<li>U+F03C8 : not included in any glyphset definition</li>
<li>U+F03C9 : not included in any glyphset definition</li>
<li>U+F03CA : not included in any glyphset definition</li>
<li>U+F03CB : not included in any glyphset definition</li>
<li>U+F03CC : not included in any glyphset definition</li>
<li>U+F03CD : not included in any glyphset definition</li>
<li>U+F03CE : not included in any glyphset definition</li>
<li>U+F03CF : not included in any glyphset definition</li>
<li>U+F03D0 : not included in any glyphset definition</li>
<li>U+F03D1 : not included in any glyphset definition</li>
<li>U+F03D2 : not included in any glyphset definition</li>
<li>U+F03D3 : not included in any glyphset definition</li>
<li>U+F03D4 : not included in any glyphset definition</li>
<li>U+F03D5 : not included in any glyphset definition</li>
<li>U+F03D6 : not included in any glyphset definition</li>
<li>U+F03DE : not included in any glyphset definition</li>
<li>U+F03DF : not included in any glyphset definition</li>
<li>U+F03E0 : not included in any glyphset definition</li>
<li>U+F03E1 : not included in any glyphset definition</li>
<li>U+F03E2 : not included in any glyphset definition</li>
<li>U+F03E3 : not included in any glyphset definition</li>
<li>U+F03E4 : not included in any glyphset definition</li>
<li>U+F03EB : not included in any glyphset definition</li>
<li>U+F03EC : not included in any glyphset definition</li>
<li>U+F03ED : not included in any glyphset definition</li>
<li>U+F03F4 : not included in any glyphset definition</li>
<li>U+F03F5 : not included in any glyphset definition</li>
<li>U+F03F6 : not included in any glyphset definition</li>
<li>U+F03F7 : not included in any glyphset definition</li>
<li>U+F0400 : not included in any glyphset definition</li>
<li>U+F0401 : not included in any glyphset definition</li>
<li>U+F0402 : not included in any glyphset definition</li>
<li>U+F0403 : not included in any glyphset definition</li>
<li>U+F0404 : not included in any glyphset definition</li>
<li>U+F0405 : not included in any glyphset definition</li>
<li>U+F0406 : not included in any glyphset definition</li>
<li>U+F040D : not included in any glyphset definition</li>
<li>U+F040E : not included in any glyphset definition</li>
<li>U+F040F : not included in any glyphset definition</li>
<li>U+F0410 : not included in any glyphset definition</li>
<li>U+F0411 : not included in any glyphset definition</li>
<li>U+F0412 : not included in any glyphset definition</li>
<li>U+F0413 : not included in any glyphset definition</li>
<li>U+F0414 : not included in any glyphset definition</li>
<li>U+F0415 : not included in any glyphset definition</li>
<li>U+F0416 : not included in any glyphset definition</li>
<li>U+F0417 : not included in any glyphset definition</li>
<li>U+F0418 : not included in any glyphset definition</li>
<li>U+F0419 : not included in any glyphset definition</li>
<li>U+F041A : not included in any glyphset definition</li>
<li>U+F041B : not included in any glyphset definition</li>
<li>U+F041C : not included in any glyphset definition</li>
<li>U+F041D : not included in any glyphset definition</li>
<li>U+F041E : not included in any glyphset definition</li>
<li>U+F041F : not included in any glyphset definition</li>
<li>U+F0420 : not included in any glyphset definition</li>
<li>U+F0421 : not included in any glyphset definition</li>
<li>U+F0422 : not included in any glyphset definition</li>
<li>U+F0423 : not included in any glyphset definition</li>
<li>U+F0424 : not included in any glyphset definition</li>
<li>U+F0425 : not included in any glyphset definition</li>
<li>U+F0426 : not included in any glyphset definition</li>
<li>U+F0427 : not included in any glyphset definition</li>
<li>U+F0428 : not included in any glyphset definition</li>
<li>U+F0429 : not included in any glyphset definition</li>
<li>U+F042A : not included in any glyphset definition</li>
<li>U+F0431 : not included in any glyphset definition</li>
<li>U+F0432 : not included in any glyphset definition</li>
<li>U+F0433 : not included in any glyphset definition</li>
<li>U+F0434 : not included in any glyphset definition</li>
<li>U+F043B : not included in any glyphset definition</li>
<li>U+F043C : not included in any glyphset definition</li>
<li>U+F043D : not included in any glyphset definition</li>
<li>U+F043E : not included in any glyphset definition</li>
<li>U+F043F : not included in any glyphset definition</li>
<li>U+F0440 : not included in any glyphset definition</li>
<li>U+F0441 : not included in any glyphset definition</li>
<li>U+F0442 : not included in any glyphset definition</li>
<li>U+F0443 : not included in any glyphset definition</li>
<li>U+F0444 : not included in any glyphset definition</li>
<li>U+F0445 : not included in any glyphset definition</li>
<li>U+F044C : not included in any glyphset definition</li>
<li>U+F044D : not included in any glyphset definition</li>
<li>U+F044E : not included in any glyphset definition</li>
<li>U+F044F : not included in any glyphset definition</li>
<li>U+F0450 : not included in any glyphset definition</li>
<li>U+F0451 : not included in any glyphset definition</li>
<li>U+F0452 : not included in any glyphset definition</li>
<li>U+F0453 : not included in any glyphset definition</li>
<li>U+F0454 : not included in any glyphset definition</li>
<li>U+F0455 : not included in any glyphset definition</li>
<li>U+F0456 : not included in any glyphset definition</li>
<li>U+F0457 : not included in any glyphset definition</li>
<li>U+F0458 : not included in any glyphset definition</li>
<li>U+F0459 : not included in any glyphset definition</li>
<li>U+F0460 : not included in any glyphset definition</li>
<li>U+F0461 : not included in any glyphset definition</li>
<li>U+F0462 : not included in any glyphset definition</li>
<li>U+F0463 : not included in any glyphset definition</li>
<li>U+F0464 : not included in any glyphset definition</li>
<li>U+F0465 : not included in any glyphset definition</li>
<li>U+F0476 : not included in any glyphset definition</li>
<li>U+F047D : not included in any glyphset definition</li>
<li>U+F047E : not included in any glyphset definition</li>
<li>U+F047F : not included in any glyphset definition</li>
<li>U+F0480 : not included in any glyphset definition</li>
<li>U+F0481 : not included in any glyphset definition</li>
<li>U+F0482 : not included in any glyphset definition</li>
<li>U+F0489 : not included in any glyphset definition</li>
<li>U+F048A : not included in any glyphset definition</li>
<li>U+F048B : not included in any glyphset definition</li>
<li>U+F048C : not included in any glyphset definition</li>
<li>U+F048D : not included in any glyphset definition</li>
<li>U+F048E : not included in any glyphset definition</li>
<li>U+F048F : not included in any glyphset definition</li>
<li>U+F0490 : not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>glagolitic</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ i̓ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ і́</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ i̇ ǐ ȉ ȋ i̒ i̔ i̾ i̿ i͐ i͛ i҃ i҄ i҅ i҆ i҇ i᷀ i᷁ iⷠ iⷡ</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Lithuanian (Latn, 2,357,094 speakers), Belarusian (Cyrl, 10,064,517 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Teke-Ebo (Latn, 260,000 speakers), Nateni (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Han (Latn, 6 speakers), Koonzime (Latn, 40,000 speakers), South Central Banda (Latn, 244,000 speakers), Ma’di (Latn, 584,000 speakers), Abua (Latn, 25,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ekpeye (Latn, 226,000 speakers), Western Krahn (Latn, 97,800 speakers), Northern Tutchone (Latn, 85 speakers), Bafut (Latn, 158,146 speakers), Navajo (Latn, 166,319 speakers), Ejagham (Latn, 120,000 speakers), Sar (Latn, 500,000 speakers), Ikwere (Latn, 717,000 speakers), Southern Kisi (Latn, 360,000 speakers), Makaa (Latn, 221,000 speakers), Zapotec (Latn, 490,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Aghem (Latn, 38,843 speakers), Ebira (Latn, 2,200,000 speakers), Vute (Latn, 21,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Nzakara (Latn, 50,000 speakers), Igbo (Latn, 27,823,640 speakers), Fur (Latn, 1,230,163 speakers), Dii (Latn, 71,000 speakers), Basaa (Latn, 332,940 speakers), Mfumte (Latn, 79,000 speakers), Cicipu (Latn, 44,000 speakers), Avokaya (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mundani (Latn, 34,000 speakers), Kom (Latn, 360,685 speakers), Dutch (Latn, 31,709,104 speakers), Yala (Latn, 200,000 speakers), Keliko (Latn, 63,000 speakers), Longto (Latn, 5,000 speakers), Mango (Latn, 77,000 speakers), Heiltsuk (Latn, 300 speakers), Kaska (Latn, 125 speakers), Southern Tutchone (Latn, 65 speakers), Dan (Latn, 1,099,244 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* afii10030 (U+041C): B&lt;&lt;241.0,280.5&gt;-&lt;233.0,320.0&gt;-&lt;225.0,361.0&gt;&gt;/L&lt;&lt;225.0,361.0&gt;--&lt;225.0,22.0&gt;&gt; = 11.04094018032372

* afii10030 (U+041C): L&lt;&lt;540.0,22.0&gt;--&lt;540.0,361.0&gt;&gt;/B&lt;&lt;540.0,361.0&gt;-&lt;530.0,308.0&gt;-&lt;521.0,265.0&gt;&gt; = 10.684912400002695

* u1E00C (U+1E00C): B&lt;&lt;-264.5,668.5&gt;-&lt;-238.0,614.0&gt;-&lt;-228.0,557.0&gt;&gt;/B&lt;&lt;-228.0,557.0&gt;-&lt;-228.0,565.0&gt;-&lt;-218.5,576.5&gt;&gt; = 9.950626687951587

* u1F312 (U+1F312): B&lt;&lt;468.0,49.0&gt;-&lt;442.0,33.0&gt;-&lt;425.0,33.0&gt;&gt;/B&lt;&lt;425.0,33.0&gt;-&lt;432.0,32.0&gt;-&lt;435.0,32.0&gt;&gt; = 8.13010235415596

* u1F318 (U+1F318): B&lt;&lt;376.5,763.0&gt;-&lt;384.0,766.0&gt;-&lt;393.0,768.0&gt;&gt;/L&lt;&lt;393.0,768.0&gt;--&lt;379.0,768.0&gt;&gt; = 12.528807709151492

* u1F377 (U+1F377): B&lt;&lt;466.5,415.5&gt;-&lt;489.0,424.0&gt;-&lt;507.0,431.0&gt;&gt;/B&lt;&lt;507.0,431.0&gt;-&lt;499.0,430.0&gt;-&lt;487.5,430.0&gt;&gt; = 14.12548915823142

* u1F41F (U+1F41F): B&lt;&lt;516.0,308.0&gt;-&lt;543.0,314.0&gt;-&lt;730.0,332.0&gt;&gt;/B&lt;&lt;730.0,332.0&gt;-&lt;702.0,336.0&gt;-&lt;675.5,337.5&gt;&gt; = 13.62826507913694

* u1F41F (U+1F41F): L&lt;&lt;833.0,445.0&gt;--&lt;914.0,405.0&gt;&gt;/B&lt;&lt;914.0,405.0&gt;-&lt;900.0,416.0&gt;-&lt;900.0,434.0&gt;&gt; = 11.875815566048908

* uni046E (U+046E): B&lt;&lt;304.0,457.0&gt;-&lt;262.0,424.0&gt;-&lt;260.0,424.0&gt;&gt;/B&lt;&lt;260.0,424.0&gt;-&lt;294.0,421.0&gt;-&lt;311.0,414.0&gt;&gt; = 5.042451069170885

* uni046F (U+046F): B&lt;&lt;210.0,319.0&gt;-&lt;182.0,297.0&gt;-&lt;179.0,297.0&gt;&gt;/B&lt;&lt;179.0,297.0&gt;-&lt;215.0,292.0&gt;-&lt;239.0,278.5&gt;&gt; = 7.907162702958418

* uni263D (U+263D): B&lt;&lt;117.0,764.0&gt;-&lt;107.0,766.0&gt;-&lt;96.0,767.0&gt;&gt;/B&lt;&lt;96.0,767.0&gt;-&lt;110.0,763.0&gt;-&lt;128.5,749.0&gt;&gt; = 10.750966993188039

* uni263D (U+263D): B&lt;&lt;124.5,28.5&gt;-&lt;113.0,20.0&gt;-&lt;106.0,20.0&gt;&gt;/B&lt;&lt;106.0,20.0&gt;-&lt;113.0,19.0&gt;-&lt;116.0,18.5&gt;&gt; = 8.13010235415596

* uni263E (U+263E): B&lt;&lt;359.5,749.0&gt;-&lt;378.0,763.0&gt;-&lt;392.0,767.0&gt;&gt;/B&lt;&lt;392.0,767.0&gt;-&lt;382.0,766.0&gt;-&lt;372.0,764.0&gt;&gt; = 10.234802763423207

* uni263E (U+263E): B&lt;&lt;372.0,18.5&gt;-&lt;375.0,19.0&gt;-&lt;382.0,20.0&gt;&gt;/B&lt;&lt;382.0,20.0&gt;-&lt;376.0,20.0&gt;-&lt;364.0,28.5&gt;&gt; = 8.13010235415596

* uni2C17.salt (U+EC66): B&lt;&lt;52.0,455.0&gt;-&lt;94.0,507.0&gt;-&lt;199.0,507.0&gt;&gt;/L&lt;&lt;199.0,507.0&gt;--&lt;172.0,513.0&gt;&gt; = 12.528807709151522

* uniA666 (U+A666): B&lt;&lt;241.0,280.5&gt;-&lt;233.0,320.0&gt;-&lt;225.0,361.0&gt;&gt;/L&lt;&lt;225.0,361.0&gt;--&lt;225.0,22.0&gt;&gt; = 11.04094018032372

* uniA666 (U+A666): L&lt;&lt;540.0,22.0&gt;--&lt;540.0,361.0&gt;&gt;/B&lt;&lt;540.0,361.0&gt;-&lt;530.0,308.0&gt;-&lt;521.0,265.0&gt;&gt; = 10.684912400002695

* uniE0BB (U+E0BB): B&lt;&lt;-85.0,695.0&gt;-&lt;-99.0,684.0&gt;-&lt;-100.0,684.0&gt;&gt;/B&lt;&lt;-100.0,684.0&gt;-&lt;-90.0,682.0&gt;-&lt;-82.0,680.0&gt;&gt; = 11.309932474020195

* uniED13 (U+ED13): B&lt;&lt;210.0,319.0&gt;-&lt;182.0,297.0&gt;-&lt;179.0,297.0&gt;&gt;/B&lt;&lt;179.0,297.0&gt;-&lt;215.0,292.0&gt;-&lt;239.0,278.5&gt;&gt; = 7.907162702958418
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* Ebreve (U+0114): L&lt;&lt;127.0,126.0&gt;--&lt;126.0,521.0&gt;&gt;

* Edotaccent (U+0116): L&lt;&lt;126.0,126.0&gt;--&lt;127.0,521.0&gt;&gt;

* M (U+004D): L&lt;&lt;675.0,147.0&gt;--&lt;672.0,550.0&gt;&gt;

* afii10021 (U+0414): L&lt;&lt;168.0,649.0&gt;--&lt;484.0,650.0&gt;&gt;

* afii10024 (U+0416): L&lt;&lt;62.0,448.0&gt;--&lt;61.0,628.0&gt;&gt;

* afii10024 (U+0416): L&lt;&lt;781.0,628.0&gt;--&lt;780.0,448.0&gt;&gt;

* ij (U+0133): L&lt;&lt;449.0,451.0&gt;--&lt;450.0,115.0&gt;&gt;

* k (U+006B): L&lt;&lt;517.0,0.0&gt;--&lt;373.0,-1.0&gt;&gt;

* kcommaaccent (U+0137): L&lt;&lt;517.0,0.0&gt;--&lt;373.0,-1.0&gt;&gt;

* onequarter (U+00BC): L&lt;&lt;216.0,635.0&gt;--&lt;215.0,361.0&gt;&gt;

* u1E000 (U+1E000): L&lt;&lt;-170.0,602.0&gt;--&lt;-171.0,478.0&gt;&gt;

* u1E000 (U+1E000): L&lt;&lt;-231.0,478.0&gt;--&lt;-232.0,598.0&gt;&gt;

* u1E021 (U+1E021): L&lt;&lt;-65.0,458.0&gt;--&lt;-354.0,459.0&gt;&gt;

* u1E023 (U+1E023): L&lt;&lt;-284.0,740.0&gt;--&lt;-285.0,615.0&gt;&gt;

* uF0139 (U+F0139): L&lt;&lt;536.0,245.0&gt;--&lt;535.0,385.0&gt;&gt;

* uF02EA (U+F02EA): L&lt;&lt;296.0,1.0&gt;--&lt;174.0,0.0&gt;&gt;

* uF02EB (U+F02EB): L&lt;&lt;345.0,1.0&gt;--&lt;223.0,0.0&gt;&gt;

* uF02F3 (U+F02F3): L&lt;&lt;174.0,1.0&gt;--&lt;53.0,0.0&gt;&gt;

* uF02F4 (U+F02F4): L&lt;&lt;326.0,1.0&gt;--&lt;204.0,0.0&gt;&gt;

* uF030B (U+F030B): L&lt;&lt;796.0,1.0&gt;--&lt;674.0,0.0&gt;&gt;

* uF031A (U+F031A): L&lt;&lt;1455.0,1.0&gt;--&lt;1334.0,0.0&gt;&gt;

* uF0329 (U+F0329): L&lt;&lt;1438.0,1.0&gt;--&lt;1316.0,0.0&gt;&gt;

* uF032D (U+F032D): L&lt;&lt;1430.0,-3.0&gt;--&lt;1309.0,-4.0&gt;&gt;

* uF032E (U+F032E): L&lt;&lt;1430.0,-3.0&gt;--&lt;1309.0,-4.0&gt;&gt;

* uF032F (U+F032F): L&lt;&lt;1430.0,-3.0&gt;--&lt;1309.0,-4.0&gt;&gt;

* uF032F (U+F032F): L&lt;&lt;1832.0,278.0&gt;--&lt;1954.0,279.0&gt;&gt;

* uF0337 (U+F0337): L&lt;&lt;1641.0,1.0&gt;--&lt;1520.0,0.0&gt;&gt;

* uF0352 (U+F0352): L&lt;&lt;1484.0,-2.0&gt;--&lt;1362.0,-3.0&gt;&gt;

* uF0361 (U+F0361): L&lt;&lt;601.0,1.0&gt;--&lt;480.0,0.0&gt;&gt;

* uF0379 (U+F0379): L&lt;&lt;1018.0,1.0&gt;--&lt;896.0,0.0&gt;&gt;

* uF037A (U+F037A): L&lt;&lt;1018.0,1.0&gt;--&lt;896.0,0.0&gt;&gt;

* uF0392 (U+F0392): L&lt;&lt;1006.0,1.0&gt;--&lt;885.0,0.0&gt;&gt;

* uF0394 (U+F0394): L&lt;&lt;1006.0,1.0&gt;--&lt;885.0,0.0&gt;&gt;

* uF039D (U+F039D): L&lt;&lt;585.0,1.0&gt;--&lt;464.0,0.0&gt;&gt;

* uF039F (U+F039F): L&lt;&lt;585.0,1.0&gt;--&lt;464.0,0.0&gt;&gt;

* uF03A0 (U+F03A0): L&lt;&lt;585.0,1.0&gt;--&lt;464.0,0.0&gt;&gt;

* uF03D4 (U+F03D4): L&lt;&lt;1220.0,1.0&gt;--&lt;1099.0,0.0&gt;&gt;

* uF03D5 (U+F03D5): L&lt;&lt;1233.0,1.0&gt;--&lt;1111.0,0.0&gt;&gt;

* uF03D6 (U+F03D6): L&lt;&lt;1233.0,1.0&gt;--&lt;1111.0,0.0&gt;&gt;

* uF03DF (U+F03DF): L&lt;&lt;1357.0,1.0&gt;--&lt;1235.0,0.0&gt;&gt;

* uF03F4 (U+F03F4): L&lt;&lt;620.0,1.0&gt;--&lt;498.0,0.0&gt;&gt;

* uF03F5 (U+F03F5): L&lt;&lt;620.0,1.0&gt;--&lt;498.0,0.0&gt;&gt;

* uF0400 (U+F0400): L&lt;&lt;620.0,1.0&gt;--&lt;498.0,0.0&gt;&gt;

* uF040D (U+F040D): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF040F (U+F040F): L&lt;&lt;1227.0,1.0&gt;--&lt;1106.0,0.0&gt;&gt;

* uF0410 (U+F0410): L&lt;&lt;1227.0,1.0&gt;--&lt;1106.0,0.0&gt;&gt;

* uF0417 (U+F0417): L&lt;&lt;1225.0,1.0&gt;--&lt;1104.0,0.0&gt;&gt;

* uF0418 (U+F0418): L&lt;&lt;1249.0,1.0&gt;--&lt;1127.0,0.0&gt;&gt;

* uF041B (U+F041B): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF041C (U+F041C): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF041E (U+F041E): L&lt;&lt;812.0,1.0&gt;--&lt;691.0,0.0&gt;&gt;

* uF041F (U+F041F): L&lt;&lt;812.0,1.0&gt;--&lt;690.0,0.0&gt;&gt;

* uF0420 (U+F0420): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF0421 (U+F0421): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF0422 (U+F0422): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF0423 (U+F0423): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF0425 (U+F0425): L&lt;&lt;1227.0,1.0&gt;--&lt;1106.0,0.0&gt;&gt;

* uF0427 (U+F0427): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF0427 (U+F0427): L&lt;&lt;812.0,1.0&gt;--&lt;690.0,0.0&gt;&gt;

* uF0428 (U+F0428): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uF0450 (U+F0450): L&lt;&lt;1444.0,1.0&gt;--&lt;1322.0,0.0&gt;&gt;

* uF0464 (U+F0464): L&lt;&lt;795.0,1.0&gt;--&lt;674.0,0.0&gt;&gt;

* uF0465 (U+F0465): L&lt;&lt;795.0,1.0&gt;--&lt;674.0,0.0&gt;&gt;

* uF0489 (U+F0489): L&lt;&lt;819.0,1.0&gt;--&lt;697.0,0.0&gt;&gt;

* uni2C02.ss03.salt (U+EC77): L&lt;&lt;279.0,373.0&gt;--&lt;278.0,589.0&gt;&gt;

* uni2C0B.ss04 (U+F027B): L&lt;&lt;162.0,3.0&gt;--&lt;41.0,2.0&gt;&gt;

* uni2C0F.ss03.salt (U+EC7E): L&lt;&lt;691.0,647.0&gt;--&lt;829.0,648.0&gt;&gt;

* uni2C23 (U+2C23): L&lt;&lt;158.0,660.0&gt;--&lt;528.0,659.0&gt;&gt;

* uni2C23 (U+2C23): L&lt;&lt;230.0,597.0&gt;--&lt;229.0,225.0&gt;&gt;

* uni2C26.ss03 (U+F0226): L&lt;&lt;184.0,308.0&gt;--&lt;357.0,307.0&gt;&gt;

* uni2C26.ss03 (U+F0226): L&lt;&lt;443.0,307.0&gt;--&lt;616.0,308.0&gt;&gt;

* uni2C29.ss03 (U+F0229): L&lt;&lt;184.0,308.0&gt;--&lt;357.0,307.0&gt;&gt;

* uni2C29.ss03 (U+F0229): L&lt;&lt;443.0,307.0&gt;--&lt;616.0,308.0&gt;&gt;

* uni2C2D (U+2C2D): L&lt;&lt;436.0,-1.0&gt;--&lt;434.0,275.0&gt;&gt;

* uni2C2D (U+2C2D): L&lt;&lt;528.0,663.0&gt;--&lt;529.0,-1.0&gt;&gt;

* uni2C34.ss03 (U+F0234): L&lt;&lt;601.0,1.0&gt;--&lt;480.0,0.0&gt;&gt;

* uni2C3D (U+2C3D): L&lt;&lt;315.0,284.0&gt;--&lt;314.0,166.0&gt;&gt;

* uni2C42.ss03 (U+F0242): L&lt;&lt;391.0,1.0&gt;--&lt;269.0,0.0&gt;&gt;

* uni2C47.salt (U+EC67): L&lt;&lt;316.0,-4.0&gt;--&lt;315.0,-163.0&gt;&gt;

* uni2C50.ss03.salt (U+EC91): L&lt;&lt;363.0,-3.0&gt;--&lt;241.0,-4.0&gt;&gt;

* uni2C53 (U+2C53): L&lt;&lt;127.0,460.0&gt;--&lt;416.0,459.0&gt;&gt;

* uni2C53 (U+2C53): L&lt;&lt;184.0,416.0&gt;--&lt;183.0,56.0&gt;&gt;

* uni2C5A.ss03 (U+F025A): L&lt;&lt;523.0,-161.0&gt;--&lt;401.0,-162.0&gt;&gt;

* uni2C5D (U+2C5D): L&lt;&lt;303.0,0.0&gt;--&lt;302.0,186.0&gt;&gt;

* uni2C5D (U+2C5D): L&lt;&lt;373.0,478.0&gt;--&lt;374.0,0.0&gt;&gt;

* uni2DE0 (U+2DE0): L&lt;&lt;-218.0,762.0&gt;--&lt;-86.0,763.0&gt;&gt;

* uni2E43 (U+2E43): L&lt;&lt;492.0,160.0&gt;--&lt;808.0,158.0&gt;&gt;

* uniA658 (U+A658): L&lt;&lt;364.0,277.0&gt;--&lt;168.0,276.0&gt;&gt;

* uniA659 (U+A659): L&lt;&lt;256.0,194.0&gt;--&lt;119.0,193.0&gt;&gt;

* uniA65C (U+A65C): L&lt;&lt;629.0,277.0&gt;--&lt;433.0,276.0&gt;&gt;

* uniA65D (U+A65D): L&lt;&lt;417.0,194.0&gt;--&lt;280.0,193.0&gt;&gt;

* uniA662 (U+A662): L&lt;&lt;168.0,649.0&gt;--&lt;635.0,650.0&gt;&gt;

* uniEC9E (U+EC9E): L&lt;&lt;-136.0,458.0&gt;--&lt;-137.0,574.0&gt;&gt;

* uniEC9F (U+EC9F): L&lt;&lt;-111.0,457.0&gt;--&lt;-110.0,693.0&gt;&gt;

* uniEC9F (U+EC9F): L&lt;&lt;-229.0,457.0&gt;--&lt;-228.0,686.0&gt;&gt;

* uniECA5 (U+ECA5): L&lt;&lt;601.0,1.0&gt;--&lt;480.0,0.0&gt;&gt;

* uniED26 (U+ED26): L&lt;&lt;256.0,194.0&gt;--&lt;119.0,193.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value '    ' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 1 | 0 | 4 | 17 | 107 | 6 | 101 | 0 | 
| 0% | 0% | 2% | 7% | 45% | 3% | 43% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG

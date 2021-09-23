---
title: orientation
slug: Web/SVG/Attribute/orientation
tags:
  - Deprecated
  - SVG
  - SVG Attribute
browser-compat: svg.elements.glyph.orientation
---
<div>{{SVGRef}}{{Deprecated_Header}}</div>

<p>The <code><strong>orientation</strong></code> attribute indicates that the given {{Glossary("glyph")}} is only to be used for a particular text direction, i.e. horizontal or vertical.</p>

<p>You can use this attribute with the following SVG elements:</p>

<ul>
  <li>{{SVGElement("glyph")}}</li>
</ul>

<h2 id="Usage_notes">Usage notes</h2>

<table class="properties">
 <tbody>
  <tr>
   <th scope="row">Value</th>
   <td><code>h</code> | <code>v</code></td>
  </tr>
  <tr>
   <th scope="row">Default value</th>
   <td><em>None (meaning glyph can be used for both text directions)</em></td>
  </tr>
  <tr>
   <th scope="row">Animatable</th>
   <td>Yes</td>
  </tr>
 </tbody>
</table>

<dl>
 <dt><code>h</code></dt>
 <dd>This value indicates that the glyph is only used for a horizontal text direction.</dd>
 <dt><code>v</code></dt>
 <dd>This value indicates that the glyph is only used for a vertical text direction.</dd>
</dl>

<h2 id="Specifications">Specifications</h2>

<table class="no-markdown">
 <thead>
  <tr>
   <th scope="col">Specification</th>
   <th scope="col">Status</th>
   <th scope="col">Comment</th>
  </tr>
 </thead>
 <tbody>
  <tr>
   <td>{{SpecName("SVG1.1", "fonts.html#GlyphElementOrientationAttribute", "orientation")}}</td>
   <td>{{Spec2("SVG1.1")}}</td>
   <td>Initial definition</td>
  </tr>
 </tbody>
</table>

<h2 id="Browser_compatibility">Browser compatibility</h2>

<p>{{Compat}}</p>
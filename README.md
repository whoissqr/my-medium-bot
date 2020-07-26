# my-medium-bot

<!DOCTYPE html>
<!--[if lte IE 9]>
<html class="ie" lang="en">
<![endif]-->
<!--[if gt IE 9]><!-->
<html lang="en">
<!--<![endif]-->
<head>
<meta charset="UTF-8">
<title>Medium API, blog posts from Medium </title>
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:site" content="@CodePen">
<meta name="twitter:title" content="Medium API, blog posts from Medium ">
<meta name="twitter:description" content="...">
<meta name="twitter:image" content="https://assets.codepen.io/1493964/internal/screenshots/pens/ZoQRoz.default.png?fit=cover&amp;format=auto&amp;ha=false&amp;height=720&amp;quality=75&amp;v=2&amp;version=1524510659&amp;width=1279">
<meta property="og:image" content="https://assets.codepen.io/1493964/internal/screenshots/pens/ZoQRoz.default.png?fit=cover&amp;format=auto&amp;ha=false&amp;height=720&amp;quality=75&amp;v=2&amp;version=1524510659&amp;width=1279" itemprop="thumbnailUrl">
<meta property="og:title" content="Medium API, blog posts from Medium ">
<meta property="og:url" content="https://codepen.io/Konrad29/details/ZoQRoz">
<meta property="og:site_name" content="CodePen">
<meta property="og:description" content="...">
<link rel="alternate" type="application/json+oembed" href="https://codepen.io/api/oembed?url=https%3A%2F%2Fcodepen.io%2FKonrad29%2Fpen%2FZoQRoz&format=json" title="Medium API, blog posts from Medium " />
<link href="https://fonts.googleapis.com/css?family=Lato:300,400,400italic,700,700italic,900,900italic" rel="stylesheet" />
<link rel="stylesheet" media="all" href="https://static.codepen.io/assets/global/global-5d2dff84c4c44b3831be8b188e5a6f2170a6a8385fb372550697f100b70b2819.css" />
<link rel="stylesheet" media="screen" href="https://static.codepen.io/assets/packs/css/2-0b73550e.chunk.css" />
<link rel="stylesheet" media="screen" href="https://static.codepen.io/assets/packs/css/everypage-6a532bbe.css" />
<link rel="stylesheet" media="all" href="https://static.codepen.io/assets/editor/editor-36ff8a57930886fcf489e47e57dba4675fe014ba5afd96e328aa13c653ecbedd.css" />
<meta name="description" content="...">
<link rel="stylesheet" media="screen" href="https://static.codepen.io/assets/editor/themes/twilight-bbb3d58f8024c27567f788f3990f2dce8754c2b67246bf12ad766768fe51955b.css" id="cm-theme" />
<style id="cm-font-family" class="cm-font-family">
  
      
  .CodeMirror,
  .console-logs .console-line,
  .console-command-line-input,
  .console-message,
  .CodeMirror-hint {
    font-family: Monaco, MonoSpace;
  }
</style>
<style id="cm-font-size">
  .CodeMirror,
  .console-logs .console-line,
  .console-command-line-input,
  .console-message,
  .CodeMirror-hint {
    font-size: 14px;
  }
</style>
<link rel="apple-touch-icon" type="image/png" href="https://static.codepen.io/assets/favicon/apple-touch-icon-5ae1a0698dcc2402e9712f7d01ed509a57814f994c660df9f7a952f3060705ee.png" />
<meta name="apple-mobile-web-app-title" content="CodePen">
<link rel="shortcut icon" type="image/x-icon" href="https://static.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico" />
<link rel="mask-icon" type="" href="https://static.codepen.io/assets/favicon/logo-pin-8f3771b1072e3c38bd662872f6b673a722f4b3ca2421637d5596661b4e2132cc.svg" color="#111" />
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="ILrDSCpv7vX+ldRRe2oFzXTIHWaH7cFnMUEb+0+HCDO3vPvMCBghafKXmKdELMEImjivdf3mxqTot95O99f/wA==" />
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="monetization" content="$ilp.uphold.com/biyqg2MkQKbe">
<script>/* Firefox needs this to prevent FOUC. */</script>
</head>
<body class="room-editor editor state-htmlOn-cssOn-jsOn sidebar-false preload prelayout
  layout-top
 logged-in ">
<header class="main-header" id="main-header">
</header>
<div class="item-settings-modal tab-layout tab-layout-modal pen  item-settings-modal-half" id="item-settings-modal">
<header class="item-settings-modal-header tab-layout-header">
<h2 class="item-settings-modal-header-title tab-layout-header-title">Pen Settings</h2>
<div class="save-and-close-wrap">
<button type="button" class="button mini-button button-no-right-margin close" id="top-close-settings">
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
</button>
</div>
</header>
<div class="tabs tab-layout-wrapper settings-tabs-wrapper">
<nav id="settings-tabs" class="no-mobile-nav tab-layout-tabs item-settings-tabs">
<div class="tab-layout-tab-group">
<a id="settings-html-tab" href="#settings-html" class="settings-tab-html" data-type="html">
HTML
</a>
<a id="settings-css-tab" href="#settings-css" class="settings-tab-css" data-type="css">
CSS
</a>
<a id="settings-js-tab" href="#settings-js" class="settings-tab-js" data-type="js">
JS
</a>
</div>
<div class="tab-layout-tab-group">
<a id="settings-behavior-tab" href="#settings-behavior" class="settings-tab-behavior" data-type="behavior">
Behavior
</a>
<a id="settings-editor-tab" href="#settings-editor" class="settings-tab-editor" data-type="editor">
Editor
</a>
</div>
</nav>
<div class="settings tab-page" id="settings-html">
<h3 aria-label="HTML">HTML</h3>
<form class="settings-row top-label-form normal-labels preprocessor-choice group">
<h4>
<label for="html-preprocessor">HTML Preprocessor</label>
</h4>
<div class="help-flyout-link">
<svg class="icon-help">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>About HTML Preprocessors</h5>
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>HTML preprocessors can make writing HTML more powerful or convenient. For instance, Markdown is designed to be easier to write and read for text documents and you could write a loop in Pug.</p>
<p><a href="https://blog.codepen.io/documentation/editor/using-html-preprocessors/" target="_blank" rel="noopener">Learn more</a> &middot; <a href="/versions/" target="_blank" rel="noopener">Versions</a></p>
</div>
</div>
<div class="custom-select-wrap">
<select name="html-preprocessor" id="html-preprocessor" class="fullwidth">
<option value="none">None</option>
<option value="haml">Haml</option>
<option value="markdown">Markdown</option>
<option value="slim">Slim</option>
<option value="pug">Pug</option>
</select>
<div class="select-icon">
<svg class="icon-arrow-down-mini">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
<svg class="icon-arrow-down-mini">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
</div>
</div>
</form>
<form class="settings-row top-label-form normal-labels prevent-form-submit" onsubmit="return false;">
<h4>
<label for="html-classes">Add Class(es) to &lt;html></label>
</h4>
<div class="help-flyout-link">
<svg class="icon-help">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>Adding Classes</h5>
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>In CodePen, whatever you write in the HTML editor is what goes within the <code>&lt;body></code> tags in <a target="_blank" rel="noopener" href="https://blog.codepen.io/documentation/features/preview-template/">a basic HTML5 template</a>. So you don't have access to higher-up elements like the <code>&lt;html></code> tag. If you want to add classes there that can affect the whole document, this is the place to do it.</p>
</div>
</div>
<input type="text" id="html-classes" name="html-classes" class="fullwidth" placeholder="e.g. single post post-1234" maxlength="250">
</form>
<form class="settings-row top-label-form normal-labels prevent-form-submit" onsubmit="return false;">
<h4>
<label for="head-content">Stuff for &lt;head></label>
</h4>
<div class="help-flyout-link">
<svg class="icon-help">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>About the &lt;head></h5>
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>In CodePen, whatever you write in the HTML editor is what goes within the <code>&lt;body></code> tags in <a target="_blank" rel="noopener" href="https://blog.codepen.io/documentation/features/preview-template/">a basic HTML5 template</a>. If you need things in the <code>&lt;head></code> of the document, put that code here.</p>
</div>
</div>
<div class="head-content-wrapper">
<textarea id="head-content" name="head-content" class="fullwidth is-code head-content" placeholder="e.g. &lt;meta>, &lt;link>, &lt;script>"></textarea>
<span class="insecure-resource-tooltip">
<div class="help-flyout-link">
<span class="icon-help">!</span>
<div class="help-flyout help-flyout-reverse">
<svg class="icon-x">
<use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<h5>Insecure Resource</h5>
<p>The resource you are linking to is using the 'http' protocol, which may not work when the browser is using https.</p>
</div>
</div>
</span>
</div>
<button class="button mini-button button-medium" id="meta-tag-insert">↑ Insert the most common viewport meta tag</button>
</form>
</div>
<div class="settings tab-page" id="settings-css">
<h3 aria-label="CSS">CSS</h3>
<form class="settings-row settings-row-1 top-label-form normal-labels preprocessor-choice group">
<h4>
<label for="css-preprocessor">CSS Preprocessor</label>
</h4>
<div class="help-flyout-link">
<svg class="icon-help">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>About CSS Preprocessors</h5>
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>CSS preprocessors help make authoring CSS easier. All of them offer things like variables and mixins to provide convenient abstractions.</p>
<p><a href="https://blog.codepen.io/documentation/editor/using-css-preprocessors/" target="_blank">Learn more</a> &middot; <a href="/versions/" target="_blank">Versions</a></p>
</div>
</div>
<div class="custom-select-wrap">
<select name="css-preprocessor" id="css-preprocessor" class="fullwidth css-preprocessor">
<option value="none">None</option>
<option value="less">Less</option>
<option value="scss">SCSS</option>
<option value="sass">Sass</option>
<option value="stylus">Stylus</option>
<option value="postcss">PostCSS</option>
</select>
<div class="select-icon">
<svg class="icon-arrow-down-mini">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
<svg class="icon-arrow-down-mini">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
</div>
</div>
<div id="need-an-addon" class="align-right hide">
<a id="css-need-an-addon-button" href="#0" class="button button-medium mini-button need-an-addon-button">
Need an add-on?
</a>
</div>
<div class="add-ons add-ons-scss hide" id="add-ons"></div>
</form>
<form id="startercss-options-form" class="settings-row settings-row-2 top-label-form prevent-form-submit" onsubmit="return false;">
<h4>
CSS Base
</h4>
<div class="help-flyout-link">
<svg class="icon-help">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>About CSS Base</h5>
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>It's a common practice to apply CSS to a page that styles elements such that they are consistent across all browsers. We offer two of the most popular choices: <a href="https://necolas.github.io/normalize.css/" target="_blank" rel="noopener">normalize.css</a> and a <a href="http://meyerweb.com/eric/tools/css/reset/" target="_blank" rel="noopener">reset</a>. Or, choose <b>Neither</b> and nothing will be applied.</p>
</div>
</div>
<ul class="radio-list">
<li>
<input type="radio" id="startercss-normalize" name="startercss" checked value="normalize">
<label for="startercss-normalize" class="small-inline">Normalize</label>
</li>
<li>
<input type="radio" id="startercss-reset" name="startercss" checked value="reset">
<label for="startercss-reset" class="small-inline">Reset</label>
</li>
<li>
<input type="radio" id="startercss-neither" name="startercss" checked value="neither">
<label for="startercss-neither" class="small-inline">Neither</label>
</li>
</ul>
</form>
<form id="prefix-options-form" class="settings-row settings-row-3 top-label-form">
<h4>
Vendor Prefixing
</h4>
<div class="help-flyout-link">
<svg class="icon-help">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>About Vendor Prefixing</h5>
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>To get the best cross-browser support, it is a common practice to apply vendor prefixes to CSS properties and values that require them to work. For instance <code>-webkit-</code> or <code>-moz-</code>.</p>
<p>We offer two popular choices: <a href="https://github.com/postcss/autoprefixer" target="blank" rel="noopener">Autoprefixer</a> (which processes your CSS server-side) and <a href="https://leaverou.github.io/prefixfree/" target="_blank" rel="noopener">-prefix-free</a> (which applies prefixes via a script, client-side).</p>
</div>
</div>
<ul class="radio-list">
<li>
<input type="radio" id="prefix-autoprefixer" name="prefix" value="autoprefixer">
<label for="prefix-autoprefixer" class="small-inline">Autoprefixer</label>
</li>
<li>
<input type="radio" id="prefix-prefixfree" name="prefix" value="prefixfree">
<label for="prefix-prefixfree" class="small-inline">Prefixfree</label>
</li>
<li>
<input type="radio" id="prefix-neither" name="prefix" value="neither">
<label for="prefix-neither" class="small-inline">Neither</label>
</li>
</ul>
</form>
<form id="external-css-resources" class="settings-row settings-row-4 top-label-form prevent-form-submit" onsubmit="return false;">
<h4>
Add External Stylesheets/Pens
</h4>
<p>Any URL's added here will be added as <code>&lt;link></code>s in order, and before the CSS in the editor. If you link to another Pen, it will include the CSS from that Pen. If the preprocessor matches, it will attempt to combine them before processing.</p>
<div class="resource-search-bar">
<svg class="icon icon-mag">
<use xlink:href="/svg_sprite?v=20ea15c6#mag"></use>
</svg>
<input id="external-css-search" type="text" value="" placeholder="Search for resources (Bootstrap, Foundation, Animate.css...)">
</div>
<div class="algolia-shoutout">
<a href="https://www.algolia.com/?utm_source=react-instantsearch&utm_medium=website&utm_content=codepen.io&utm_campaign=poweredby" target="_blank">
Powered by <img alt="Algolia" src="https://static.codepen.io/assets/settings/algolia-9e1c0c887f4db420704b2a79926864019ef156bcecc9d5774a7e4eaa731fc5b5.svg" />
</a>
</div>
<div class="help-flyout-link">
<svg class="icon-help">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>About External Resources</h5>
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>You can apply CSS to your Pen from any stylesheet on the web. Just put a URL to it here and we'll apply it, in the order you have them, before the CSS in the Pen itself.</p>
<p>If the stylesheet you link to has the file extension of a preprocessor, we'll attempt to process it before applying.</p>
<p>You can also link to another Pen here, and we'll pull the CSS from that Pen and include it. If it's using a matching preprocessor, we'll combine the code before preprocessing, so you can use the linked Pen as a true dependency.</p>
<p><a href="https://blog.codepen.io/documentation/editor/adding-external-resources/" target="_blank" rel="noopener">Learn more</a></p>
</div>
</div>
<div id="css-external-resources" class="external-resource-wrapper">
</div>
<script id="css-external-resources-template" type="text/template">
  <div data-view-id="<%= view_id %>" class="external-resource-url-row <%= insecure_resource %>">

    <span class="move-external-url">
      <svg class="icon-drag-handle" width="20" height="17">
        <use xlink:href="/svg_sprite?v=20ea15c6#drag-handle" />
      </svg>
    </span>

    <input
      id="external-resource-input-<%= view_id %>"
      class="fullwidth css-resource external-resource"
      type="text"
      pattern="^((ftp|http|https):)?\/\/(\w+:{0,1}\w*@)?(\S+)(:[0-9]+)?(\/|\/([\w#!:.?+=&%@!\-\/]))?$"
      name="external-css"
      placeholder="<%= placeholder %>"
      value="<%= url %>"
      data-view-id="<%= view_id %>">

    <span class="insecure-resource-tooltip">
      <div class="help-flyout-link">
        <span class="icon-help">!</span>
        <div class="help-flyout help-flyout-reverse">
          <svg class="icon-x">
            <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/svg_sprite?v=20ea15c6#x"></use>
          </svg>
          <h5>Insecure Resource</h5>
          <p>You are linking to a resource using the non-secure http:// protocol, which may not work when the browser is using https:// like CodePen enforces.</p>
        </div>
      </div>
    </span>

    <div class="resource-actions">
      <span class="remove-external-url external-url-option" data-view-id="<%= view_id %>">
        <svg class="icon-x" width="12" height="12">
          <use xlink:href="/svg_sprite?v=20ea15c6#x" />
        </svg>
      </span>

      <a id="external-resource-input-view-link-<%= view_id %>" class="open-external-url external-url-option" target="_blank" rel="noopener" data-view-id="<%= view_id %>" href="<%= url %>">
        <svg class="icon-eye" width="14" height="14">
          <use xlink:href="/svg_sprite?v=20ea15c6#eye" />
        </svg>
      </a>
    </div>

  </div>
</script>
<div class="external-resource-actions group">
<span id="add-css-resource" class="button mini-button button-medium add-resource" data-type="css">
<span data-type="css">+ add another resource</span>
</span>
</div>
</form>
</div>
<div class="settings tab-page" id="settings-js">
<div class="item-settings-javascript normal-labels">
<h3 aria-label="JavaScript">JavaScript</h3>
<div class="item-settings-javascript-preprocessor settings-row">
<h4>
<label for="js-preprocessor">JavaScript Preprocessor</label>
</h4>
<div class="help-flyout-link">
<svg class="icon-help" width="14" height="14">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>About JavaScript Preprocessors</h5>
<svg class="icon-x" width="12" height="12">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>JavaScript preprocessors can help make authoring JavaScript easier and more convenient. For instance, CoffeeScript can help prevent easy-to-make mistakes and offer a cleaner syntax and Babel can bring ECMAScript 6 features to browsers that only support ECMAScript 5.</p>
<p><a href="https://blog.codepen.io/documentation/editor/using-js-preprocessors/" target="_blank" rel="noopener">Learn more</a> &middot; <a href="/versions/" target="_blank">Versions</a></p>
</div>
</div>
<div class="custom-select-wrap">
<select name="js-preprocessor" id="js-preprocessor" class="fullwidth">
<option value="none">None</option>
<option value="babel">Babel</option>
<option value="typescript">TypeScript</option>
<option value="coffeescript">CoffeeScript</option>
<option value="livescript">LiveScript</option>
</select>
<div class="select-icon">
<svg class="icon-arrow-down-mini">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
<svg class="icon-arrow-down-mini">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
</div>
</div>
<div class="processing-packages-message callout hide" id="processing-packages-message">
Babel is required to process package imports. If you need a different preprocessor remove all packages first.
</div>
</div>
<div id="external-js-resources" class="item-settings-javascript-external settings-row external-js-resources top-label-form prevent-form-submit" onsubmit="return false;">
<h4>
Add External Scripts/Pens
</h4>
<p>Any URL's added here will be added as <code>&lt;script></code>s in order, and run <em>before</em> the JavaScript in the editor. You can use the URL of any other Pen and it will include the JavaScript from that Pen.</p>
<div class="resource-search-bar">
<svg class="icon icon-mag" width="18" height="18">
<use xlink:href="/svg_sprite?v=20ea15c6#mag"></use>
</svg>
<input id="external-js-search" type="text" value="" placeholder="Search CDNjs (jQuery, Lodash, React, Angular, Vue.js, Ember...)">
</div>
<div class="algolia-shoutout">
<a href="https://www.algolia.com/?utm_source=react-instantsearch&utm_medium=website&utm_content=codepen.io&utm_campaign=poweredby" target="_blank">
Powered by <img alt="Algolia" src="https://static.codepen.io/assets/settings/algolia-9e1c0c887f4db420704b2a79926864019ef156bcecc9d5774a7e4eaa731fc5b5.svg" />
</a>
</div>
<div class="help-flyout-link">
<svg class="icon-help" width="14" height="14">
<use xlink:href="/svg_sprite?v=20ea15c6#help"></use>
</svg>
<div class="help-flyout help-flyout-reverse">
<h5>About External Resources</h5>
<svg class="icon-x" width="12" height="12">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
<p>You can apply a script from anywhere on the web to your Pen. Just put a URL to it here and we'll add it, in the order you have them, before the JavaScript in the Pen itself.</p>
<p>If the script you link to has the file extension of a preprocessor, we'll attempt to process it before applying.</p>
<p>You can also link to another Pen here, and we'll pull the JavaScript from that Pen and include it. If it's using a matching preprocessor, we'll combine the code before preprocessing, so you can use the linked Pen as a true dependency.</p>
<p><a href="https://blog.codepen.io/documentation/editor/adding-external-resources/" target="_blank">Learn more</a></p>
</div>
</div>
<div id="js-external-resources" class="external-resource-wrapper">
</div>
<script id="js-external-resources-template" type="text/template">
  <div data-view-id="<%= view_id %>" class="external-resource-url-row <%= insecure_resource %>">

    <span class="move-external-url">
      <svg class="icon-drag-handle" width="20" height="17">
        <use xlink:href="/svg_sprite?v=20ea15c6#drag-handle" />
      </svg>
    </span>

    <input
      id="external-resource-input-<%= view_id %>"
      class="fullwidth js-resource external-resource"
      type="text"
      pattern="^((ftp|http|https):)?\/\/(\w+:{0,1}\w*@)?(\S+)(:[0-9]+)?(\/|\/([\w#!:.?+=&%@!\-\/]))?$"
      name="external-js"
      placeholder="<%= placeholder %>"
      value="<%= url %>"
      data-view-id="<%= view_id %>">

    <span class="insecure-resource-tooltip">
      <div class="help-flyout-link">
        <span class="icon-help">!</span>
        <div class="help-flyout help-flyout-reverse">
          <svg class="icon-x">
            <use xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="/svg_sprite?v=20ea15c6#x"></use>
          </svg>
          <h5>Insecure Resource</h5>
          <p>You are linking to a resource using the non-secure http:// protocol, which may not work when the browser is using https:// like CodePen enforces.</p>
        </div>
      </div>
    </span>

    <div class="resource-actions">
      <span class="remove-external-url external-url-option" data-view-id="<%= view_id %>">
        <svg class="icon-x" width="12" height="12">
          <use xlink:href="/svg_sprite?v=20ea15c6#x" />
        </svg>
      </span>

      <a id="external-resource-input-view-link-<%= view_id %>" class="open-external-url external-url-option" target="_blank" rel="noopener" data-view-id="<%= view_id %>" href="<%= url %>">
        <svg class="icon-eye" width="14" height="14">
          <use xlink:href="/svg_sprite?v=20ea15c6#eye" />
        </svg>
      </a>
    </div>

  </div>
</script>
<div class="external-resource-actions group">
<span id="add-js-resource" class="button button-medium mini-button add-resource" data-type="js">
<span data-type="js">+ add another resource</span>
</span>
</div>
</div>
</div>
</div>
<div class="settings tab-page" id="settings-behavior">
<h3 aria-label="Pen Behavior">Behavior</h3>
<div class="settings-row">
<h4>Save Automatically?</h4>
<div>
<p class="hint">If active, Pens will autosave every 30 seconds after being saved once.</p>
<div class="ios-toggle-mega-label-wrap">
<span class="ios-toggle ios-toggle-ambiguous">
<input type="checkbox" id="auto-save" name="auto-save" checked>
<label for="auto-save"></label>
<label for="auto-save" class="ios-toggle-mega-label"></label>
</span>
</div>
</div>
</div>
<div class="settings-row">
<h4>Auto-Updating Preview</h4>
<p class="hint">If enabled, the preview panel updates automatically as you code. If disabled, use the "Run" button to update.</p>
<div class="ios-toggle-mega-label-wrap">
<span class="ios-toggle ios-toggle-ambiguous">
<input type="checkbox" id="auto-run" name="auto-run" checked>
<label for="auto-run"></label>
<label for="auto-run" class="ios-toggle-mega-label"></label>
</span>
</div>
</div>
<div class="settings-row">
<h4>Format on Save</h4>
<p class="hint">If enabled, your code will be formatted when you actively save your Pen. <span style="color: #ffdc40; font-weight: bold;">Note:</span> your code becomes un-folded during formatting.</p>
<div class="ios-toggle-mega-label-wrap">
<span class="ios-toggle ios-toggle-ambiguous">
<input type="checkbox" id="format_on_save" name="format_on_save">
<label for="format_on_save"></label>
<label for="format_on_save" class="ios-toggle-mega-label"></label>
</span>
</div>
</div>
</div>
<div class="settings tab-page" id="settings-editor">
<h3 aria-label="Editor Settings">Editor Settings</h3>
<form id="editor-settings-form" class="settings-row settings-row-1 top-label-form prevent-form-submit" onsubmit="return false;">
<h4>Code Indentation</h4>
<div class="settings-row">
<ul class="radio-list">
<li>
<input type="radio" id="indent-with-spaces" name="indent-with" value="spaces" checked>
<label for="indent-with-spaces" class="small-inline">Spaces</label>
</li>
<li>
<input type="radio" id="indent-with-tabs" name="indent-with" value="tabs">
<label for="indent-with-tabs" class="small-inline">Tabs</label>
</li>
</ul>
</div>
<div class="settings-row top-label-form normal-labels">
<h4><label for="tab-size">Indent width</label></h4>
<div class="custom-select-wrap">
<select id="tab-size" class="fullwidth" name="tab-size">
<option value="1">1</option>
<option value="2">2</option>
<option value="3">3</option>
<option value="4">4</option>
<option value="5">5</option>
<option value="6">6</option>
</select>
<div class="select-icon">
<svg class="icon-arrow-down-mini">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
<svg class="icon-arrow-down-mini">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
</div>
</div>
</div>
</form>
<div class="settings-row">
<h4>Want to change your Syntax Highlighting theme, Fonts and more?</h4>
<p>Visit <a href="/settings/editor" target="_blank">your global Editor Settings</a>.</p>
<h4 style="margin-top: 1rem">Need a tour of this editor?</h4>
<p>No problem, <a target="_blank" rel="noreferrer" href="/pen/tour/welcome/start">go here to start</a>.</p>
</div>
</div>
</div>
<footer>
<div class="save-and-close-wrap">
<input type="button" class="button button-small green button-no-right-margin close" value="Close" id="close-settings">
</div>
</footer>
</div>
<div class="page-wrap twilight">
<div class="boxes">
<div class="mobile-editor-nav">
<button id="html-toggle" class="selected"><span>HTML</span></button>
<button id="css-toggle"><span>CSS</span></button>
<button id="js-toggle"><span>JS</span></button>
<button id="result-toggle" class="selected"><span>Result</span></button>
</div>
<div class="top-boxes editor-parent" data-number-of-editors="3" elementtiming="pen-editors">
<div class="editor-resizer html-editor-resizer" title="Double-click to expand."></div>
<div id="box-html" class="box box-html" data-type="html">
<div class="powers">
<div class="powers-drag-handle" title="Double-click to expand."></div>
<div class="editor-actions-left">
<button id="settings-pane-html" class="button button-medium mini-button settings-nub" data-type="html" title="Open HTML Settings">
<svg class="icon-gear" width="10" height="10">
<use xlink:href="/svg_sprite?v=20ea15c6#gear"></use>
</svg>
</button>
<h2 class="box-title html-editor-title" id="html-editor-title">
<span class="box-title-name">
HTML
</span>
<span class="box-title-preprocessor-name "></span>
</h2>
</div>
<div class="editor-actions-right">
<div class="collaborators-indicators"></div>
<button class="button mini-button button-medium editor-dropdown-button editor-dropdown-button-html" data-dropdown="#editor-dropdown-html" aria-haspopup="true" aria-expanded="false">
<span class="visually-hidden">
HTML Options
</span>
<svg class="icon-arrow-down-mini" width="10" height="10">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
</button>
<ul id="editor-dropdown-html" class="link-list is-dropdown editor-dropdown editor-dropdown-html" data-dropdown-position="css" data-dropdown-type="html">
<li class="editor-dropdown-list-item">
<button id="tidy-html" class="invisible-button tidy-code-button" data-editor-type="html">
Format HTML
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="view-compiled-html" class="invisible-button view-compiled-button" data-editor-type="html">
View Compiled HTML
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="analyze-html" class="invisible-button analyze-button" data-editor-type="html">
Analyze HTML
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="maximize-html-editor" class="invisible-button maximize-button" data-editor-type="html">
Maximize HTML Editor
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="minimize-html-editor" class="invisible-button minimize-button" data-editor-type="html">
Minimize HTML Editor
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="fold-all-html" class="invisible-button fold-all-button" data-editor-type="html">
Fold All
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="unfold-all-html" class="invisible-button unfold-all-button" data-editor-type="html">
Unfold All
</button>
</li>
</ul>
</div>
</div>
<div class="code-wrap">
<pre id="html" class="code-box" aria-labeledby="html-editor-title">
              <code>
                &lt;section id=&quot;blog&quot; class=&quot;blog&quot;&gt;
  &lt;div class=&quot;blog__header&quot;&gt;
    &lt;p class=&quot;blog__header1&quot;&gt;some of my&lt;/p&gt;
    &lt;h2 class=&quot;blog__header2&quot;&gt;Medium
      &lt;span class=&quot;blog__header2Span&quot;&gt;posts&lt;/span&gt;
    &lt;/h2&gt;
  &lt;/div&gt;
  &lt;ul class=&quot;blog__slider&quot;&gt;
    Posts go here
  &lt;/ul&gt;
  &lt;ul class=&quot;blog__counter&quot;&gt;
    &lt;li class=&quot;blog__counterItem blog__counterItem-active&quot;&gt;&lt;/li&gt;
    &lt;li class=&quot;blog__counterItem&quot;&gt;&lt;/li&gt;
    &lt;li class=&quot;blog__counterItem&quot;&gt;&lt;/li&gt;
  &lt;/ul&gt;
&lt;/section&gt;
              </code>
            </pre>
<div class="error-bar" id="error-bar-html">
<span class="error-icon" data-type="html">
!
</span>
</div>
</div>
</div>
<div class="editor-resizer css-editor-resizer" title="Double-click to expand."></div>
<div id="box-css" class="box box-css" data-type="css">
<div class="powers">
<div class="powers-drag-handle" title="Double-click to expand."></div>
<div class="editor-actions-left">
<button id="settings-pane-css" class="button button-medium mini-button settings-nub" data-type="css" title="Open CSS Settings">
<svg class="icon-gear" width="10" height="10">
<use xlink:href="/svg_sprite?v=20ea15c6#gear"></use>
</svg>
</button>
<h2 class="box-title css-editor-title" id="css-editor-title">
<span class="box-title-name">
CSS
</span>
<span class="box-title-preprocessor-name "></span>
</h2>
</div>
<div class="editor-actions-right">
<div class="collaborators-indicators"></div>
<button class="button mini-button button-medium editor-dropdown-button editor-dropdown-button-css" data-dropdown="#editor-dropdown-css" aria-haspopup="true" aria-expanded="false">
<span class="visually-hidden">
CSS Options
</span>
<svg class="icon-arrow-down-mini" width="10" height="10">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
</button>
<ul id="editor-dropdown-css" class="link-list is-dropdown editor-dropdown editor-dropdown-css" data-dropdown-position="css" data-dropdown-type="css">
<li class="editor-dropdown-list-item">
<button id="tidy-css" class="invisible-button tidy-code-button" data-editor-type="css">
Format CSS
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="view-compiled-css" class="invisible-button view-compiled-button" data-editor-type="css">
View Compiled CSS
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="analyze-css" class="invisible-button analyze-button" data-editor-type="css">
Analyze CSS
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="maximize-css-editor" class="invisible-button maximize-button" data-editor-type="css">
Maximize CSS Editor
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="minimize-css-editor" class="invisible-button minimize-button" data-editor-type="css">
Minimize CSS Editor
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="fold-all-css" class="invisible-button fold-all-button" data-editor-type="css">
Fold All
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="unfold-all-css" class="invisible-button unfold-all-button" data-editor-type="css">
Unfold All
</button>
</li>
</ul>
</div>
</div>
<div class="code-wrap">
<pre id="css" class="code-box" aria-labeledby="css-editor-title">
              <code>
                a{
  color: inherit;
  text-decoration: none;
}
ul{
   list-style: none;
}

.blog{
   margin: 3rem 1rem;
   display: flex;
   flex-direction: column;
   justify-content: center;
   align-items: center;
   &amp;__header{
      text-align: center;
   }
   &amp;__header1{
      margin: 0;
      font-size: 1.1rem;
      font-weight: 300;
      letter-spacing: .2px;
      text-transform: uppercase;
   }
   &amp;__header2{
      margin-top: .3rem;
      font-size: 1.4rem;
      font-weight: 500;
   }
   &amp;__header2Span{
      font-weight: 400;
      font-size: 1.25rem;
   }
   &amp;__slider{
      padding: 0;
      display: flex;
      flex-direction: row;
      justify-content: center
   }
   &amp;__post{
      margin: 3rem 1rem;
      width: 25%;
      -webkit-box-shadow: 9px 9px 20px 0px rgba(0,0,0, .4);
      -moz-box-shadow: 9px 9px 20px 0px rgba(0,0,0, .4);
      box-shadow: 9px 9px 20px 0px rgba(0,0,0, .4);
   }
   &amp;__topImg{
      max-width: 100%;
   }
   &amp;__content{
      padding: .8rem;
   }
   &amp;__preview{
      font-size: .95rem;
      font-weight: 300;
   }
   &amp;__title{
      margin-top: 0;
      font-size: 1.4rem;
   }
   &amp;__intro{
      line-height: 1.5;
   }
   &amp;__info{
      font-weight: 300;
   }
   &amp;__author{
      font-size: .9rem;
   }
   &amp;__date{
      font-size: .85rem;
   }

   &amp;__counter{
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: row;
   }
   &amp;__counterItem{
      height: 20px;
      width: 20px;
      margin: .5rem;
      background-color: lightgray;
      border: 1px solid lightgray;
      border-radius: 25px;
      &amp;:hover{
         cursor: pointer;
      }
   }
   &amp;__counterItem-active{
      border: 1px solid lightblue;
      background-color: lightblue;
   }
}

              </code>
            </pre>
<div class="error-bar" id="error-bar-css">
<span class="error-icon" data-type="css">
!
</span>
</div>
</div>
</div>
<div class="editor-resizer js-editor-resizer" title="Double-click to expand."></div>
<div id="box-js" class="box box-js" data-type="js">
<div class="powers">
<div class="powers-drag-handle" title="Double-click to expand."></div>
<div class="editor-actions-left">
<button id="settings-pane-js" class="button button-medium mini-button settings-nub" data-type="js" title="Open JS Settings">
<svg class="icon-gear" width="10" height="10">
<use xlink:href="/svg_sprite?v=20ea15c6#gear"></use>
</svg>
</button>
<h2 class="box-title js-editor-title" id="js-editor-title">
<span class="box-title-name">
JS
</span>
<span class="box-title-preprocessor-name "></span>
</h2>
</div>
<div class="editor-actions-right">
<div class="collaborators-indicators"></div>
<button class="button mini-button button-medium editor-dropdown-button editor-dropdown-button-js" data-dropdown="#editor-dropdown-js" aria-haspopup="true" aria-expanded="false">
<span class="visually-hidden">
JS Options
</span>
<svg class="icon-arrow-down-mini" width="10" height="10">
<use xlink:href="/svg_sprite?v=20ea15c6#arrow-down-mini"></use>
</svg>
</button>
<ul id="editor-dropdown-js" class="link-list is-dropdown editor-dropdown editor-dropdown-js" data-dropdown-position="css" data-dropdown-type="js">
<li class="editor-dropdown-list-item">
<button id="tidy-js" class="invisible-button tidy-code-button" data-editor-type="js">
Format JavaScript
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="view-compiled-js" class="invisible-button view-compiled-button" data-editor-type="js">
View Compiled JavaScript
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="analyze-js" class="invisible-button analyze-button" data-editor-type="js">
Analyze JavaScript
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="maximize-js-editor" class="invisible-button maximize-button" data-editor-type="js">
Maximize JavaScript Editor
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="minimize-js-editor" class="invisible-button minimize-button" data-editor-type="js">
Minimize JavaScript Editor
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="fold-all-js" class="invisible-button fold-all-button" data-editor-type="js">
Fold All
</button>
</li>
<li class="editor-dropdown-list-item">
<button id="unfold-all-js" class="invisible-button unfold-all-button" data-editor-type="js">
Unfold All
</button>
</li>
</ul>
</div>
</div>
<div class="code-wrap">
<pre id="js" class="code-box" aria-labeledby="js-editor-title">
              <code>
                fetch(&#39;https://api.rss2json.com/v1/api.json?rss_url=https://medium.com/feed/@kk.shichao;)
   .then((res) =&gt; res.json())
   .then((data) =&gt; {
      // Filter for acctual posts. Comments don&#39;t have categories, therefore can filter for items with categories bigger than 0
      const res = data.items //This is an array with the content. No feed, no info about author etc..
      const posts = res.filter(item =&gt; item.categories.length &gt; 0) // That&#39;s the main trick* !

      // Functions to create a short text out of whole blog&#39;s content
      function toText(node) {
         let tag = document.createElement(&#39;div&#39;)
         tag.innerHTML = node
         node = tag.innerText
         return node
      }
      function shortenText(text,startingPoint ,maxLength) {
         return text.length &gt; maxLength?
         text.slice(startingPoint, maxLength):
         text
      }

      // Put things in right spots of markup
      let output = &#39;&#39;;
      posts.forEach((item) =&gt; {
         output += `
         &lt;li class=&quot;blog__post&quot;&gt;
            &lt;a href=&quot;${item.link}&quot;&gt;
               &lt;img src=&quot;${item.thumbnail}&quot; class=&quot;blog__topImg&quot;&gt;&lt;/img&gt;
               &lt;div class=&quot;blog__content&quot;&gt;
                  &lt;div class=&quot;blog_preview&quot;&gt;
                     &lt;h2 class=&quot;blog__title&quot;&gt;${shortenText(item.title, 0, 30)+ &#39;...&#39;}&lt;/h2&gt;
                     &lt;p class=&quot;blog__intro&quot;&gt;${&#39;...&#39; + shortenText(toText(item.content),60, 300)+ &#39;...&#39;}&lt;/p&gt;
                  &lt;/div&gt;
                  &lt;hr&gt;
                  &lt;div class=&quot;blog__info&quot;&gt;
                     &lt;span class=&quot;blog__author&quot;&gt;${item.author}&lt;/span&gt;
                     &lt;span class=&quot;blog__date&quot;&gt;${shortenText(item.pubDate,0 ,10)}&lt;/span&gt;
                  &lt;/div&gt;
               &lt;/div&gt;
            &lt;a/&gt;
         &lt;/li&gt;`

      })
      document.querySelector(&#39;.blog__slider&#39;).innerHTML = output
})


              </code>
            </pre>
<div class="error-bar" id="error-bar-js">
<span class="error-icon" data-type="js">
!
</span>
</div>
</div>
</div>
</div>
<div id="resizer" class="resizer"><span></span><div id="width-readout" class="width-readout">999px</div></div>
<section id="drawer" class="drawer comments">
</section>
<div class="output-container">
<div class="output-sizer">
<div id="result_div" class="result">
<iframe id="result" name="CodePen" src="https://cdpn.io/Konrad29/fullpage/ZoQRoz" sandbox="allow-downloads allow-forms allow-modals allow-pointer-lock allow-popups allow-presentation allow-same-origin allow-scripts allow-top-navigation-by-user-activation" allow="accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; microphone; midi; payment; vr" scrolling="auto" allowTransparency="true" allowpaymentrequest="true" allowfullscreen="true" class="result-iframe ">
          </iframe>
<div id="editor-drag-cover" class="drag-cover"></div>
</div>
<div id="box-console" class="box box-console">
<div class="editor-resizer editor-resizer-console" title="Drag to resize. Double-click to expand."></div>
<div class="powers">
<div class="powers-drag-handle" title="Drag to resize. Double-click to expand."></div>
<div class="editor-actions-left">
<h2 class="box-title"><span class="box-title-name">Console</span></h2>
</div>
<div class="editor-actions-right">
<button class="button button-medium mini-button console-clear-button" title="Clear">
Clear
</button>
<button class="button button-medium mini-button close-editor-button" data-type="console" title="Close">
<svg class="icon-x">
<use xlink:href="/svg_sprite?v=20ea15c6#x"></use>
</svg>
</button>
</div>
</div>
<div class="console-wrap">
<div class="console-entries short-no-scroll"></div>
<div class="console-command-line">
<span class="console-arrow forwards"></span>
<textarea class="console-command-line-input auto-expand" rows="1" data-min-rows="1"></textarea>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<div id="asset-bin-goes-here"></div>
<footer id="react-pen-footer" class="site-footer editor-footer"></footer>
<div id="keycommands" class="modal modal-neutral">
<div class="keycommands-container">
<section class="editor-commands" style="padding-right: 10px;">
<h2>Editor Commands</h2>
<div class="key-group">
<kbd class="keycommand">
<span class="key pc_only">Ctrl</span>
<span class="key mac_only">Ctrl</span>
<span class="key">Space</span>
</kbd>
Autocomplete
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key">F</span>
</kbd>
Find
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key">G</span>
</kbd>
Find Next
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key" title="Shift">⇧</span>
<span class="key">G</span>
</kbd>
Find Previous
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key pc_only" title="Shift">⇧</span>
<span class="key mac_only">Opt</span>
<span class="key">F</span>
</kbd>
Find & Replace
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key" title="Shift">⇧</span>
<span class="key">F</span>
</kbd>
Format Code
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key">[</span>
</kbd>
Indent Code Right
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key">]</span>
</kbd>
Indent Code Left
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key" title="Shift">⇧</span>
<span class="key">Tab</span>
</kbd>
Auto Indent Code
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key">/</span>
</kbd>
Line Comment
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key pc_only" title="Shift">⇧</span>
<span class="key mac_only">Opt</span>
<span class="key">/</span>
</kbd>
Block Comment
</div>
<p style="margin: 20px 0 0 0;">Also see: <a href="https://blog.codepen.io/documentation/features/tab-triggers/" target="_blank" rel="noopener">Tab Triggers</a></p>
</section>
<section class="editor-commands">
<h2>Editor Focus</h2>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key pc_only">Alt</span>
<span class="key mac_only">Opt</span>
<span class="key">1</span>
</kbd>
HTML Editor
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key pc_only">Alt</span>
<span class="key mac_only">Opt</span>
<span class="key">2</span>
</kbd>
CSS Editor
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key pc_only">Alt</span>
<span class="key mac_only">Opt</span>
<span class="key">3</span>
</kbd>
JS Editor
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key pc_only">Alt</span>
<span class="key mac_only">Opt</span>
<span class="key">4</span>
</kbd>
Toggle Console
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key pc_only">Alt</span>
<span class="key mac_only">Opt</span>
<span class="key">0</span>
</kbd>
Preview
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key">Esc</span>
</kbd>
Exit currently focused editor
</div>
</section>
<section class="editor-commands">
<h2>Misc</h2>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key" title="Shift">⇧</span>
<span class="key">7</span>
</kbd>
Re-run Preview
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key" title="Shift">⇧</span>
<span class="key">8</span>
</kbd>
Clear All Analyze Errors
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key" title="Shift">⇧</span>
<span class="key">9</span>
</kbd>
Open This Dialog
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key" title="Shift">⇧</span>
<span class="key">0</span>
</kbd>
Open Debug View
</div>
<h2>HTML Specific</h2>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key" title="Shift">⇧</span>
<span class="key">A</span>
</kbd>
Wrap With...
</div>
<h2>Pen Actions</h2>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key">P</span>
</kbd>
Create New Pen
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key">S</span>
</kbd>
Save
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key" title="Shift">⇧</span>
<span class="key">S</span>
</kbd>
Save As Private <span class="badge badge-pro text">PRO</span>
</div>
<div class="key-group">
<kbd class="keycommand">
<span class="key -command"></span>
<span class="key">I</span>
</kbd>
Info Panel (if owned)
</div>
</section>
</div>
</div>
<div id="popup-overlay" class="overlay popup-overlay"></div>
<div id="modal-overlay" class="overlay modal-overlay"></div>
<noscript>

  <input type="checkbox" class="modal-closing-trick" id="modal-closing-trick">

  <div class="overlay noscript-overlay" style="display: block;"></div>

  <div class="modal modal-message group modal-warning">

    <div class="modal-title">CodePen requires JavaScript to render the code and preview areas in this view.</div>

    <p>Trying <a href="https://codepen.io/Konrad29/debug/ZoQRoz">viewing this Pen in Debug Mode</a>, which is the preview area without any iframe and does not require JavaScript. Although what the preview is of might!</p>

    <p>Need to know how to enable JavaScript? <a href="http://enable-javascript.com/" target="_blank" rel="noopener">Go here.</a></p>

    <label class="button button-medium" for="modal-closing-trick">Close this, use anyway.</label>

  </div>

</noscript>
<input type="hidden" id="init-data" value="{&quot;__browser&quot;:{&quot;device&quot;:&quot;unknown&quot;,&quot;mobile&quot;:null,&quot;name&quot;:&quot;chrome&quot;,&quot;platform&quot;:&quot;mac&quot;,&quot;version&quot;:&quot;84&quot;},&quot;__analytics&quot;:{&quot;controllerActionName&quot;:&quot;show&quot;,&quot;controllerName&quot;:&quot;pen&quot;,&quot;enabled&quot;:true},&quot;__CPDATA&quot;:{&quot;domain_iframe&quot;:&quot;https://cdpn.io&quot;,&quot;host&quot;:&quot;codepen.io&quot;,&quot;iframe_allow&quot;:&quot;accelerometer; ambient-light-sensor; camera; encrypted-media; geolocation; gyroscope; microphone; midi; payment; vr&quot;,&quot;iframe_sandbox&quot;:&quot;allow-downloads allow-forms allow-modals allow-pointer-lock allow-popups allow-presentation allow-same-origin allow-scripts allow-top-navigation-by-user-activation&quot;},&quot;__turnOffJS&quot;:false,&quot;__constants&quot;:{&quot;grid_iframe_sandbox_attributes&quot;:&quot;allow-scripts allow-pointer-lock allow-same-origin&quot;},&quot;__svg_sprite&quot;:&quot;/svg_sprite?v=20ea15c6&quot;,&quot;__stream_analytics&quot;:{&quot;api_key&quot;:&quot;64puhuch8n2j&quot;,&quot;token&quot;:&quot;eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJyZXNvdXJjZSI6ImFuYWx5dGljcyIsImFjdGlvbiI6IioiLCJ1c2VyX2lkIjoiKiJ9.K-TP9-k-_ZnktGVf_CxDVZyUXKzGMFVJ--dNJ-20_t4&quot;},&quot;__user&quot;:{&quot;anon&quot;:false,&quot;base_url&quot;:&quot;/sqr/&quot;,&quot;current_team_id&quot;:0,&quot;current_team_hashid&quot;:&quot;YdEzGn&quot;,&quot;hashid&quot;:&quot;ZyyjNy&quot;,&quot;id&quot;:165598,&quot;itemType&quot;:&quot;user&quot;,&quot;name&quot;:&quot;sqr&quot;,&quot;owner_id&quot;:&quot;ZyyjNyYdEzGn&quot;,&quot;paid&quot;:false,&quot;tier&quot;:0,&quot;username&quot;:&quot;sqr&quot;,&quot;created_at&quot;:&quot;2014-07-17T01:29:04.000Z&quot;,&quot;email_verified&quot;:true,&quot;collections_count&quot;:0,&quot;collections_private_count&quot;:0,&quot;followers_count&quot;:0,&quot;followings_count&quot;:0,&quot;pens_count&quot;:1,&quot;pens_private_count&quot;:0,&quot;projects_count&quot;:0,&quot;projects_private_count&quot;:0},&quot;__firebase&quot;:{&quot;config&quot;:{&quot;apiKey&quot;:&quot;AIzaSyBgLAe7N_MdFpuVofMkcQLGwwhUu5tuxls&quot;,&quot;authDomain&quot;:&quot;codepen-store-production.firebaseapp.com&quot;,&quot;databaseURL&quot;:&quot;https://codepen-store-production.firebaseio.com&quot;,&quot;disabled&quot;:false,&quot;projectId&quot;:&quot;codepen-store-production&quot;},&quot;token&quot;:&quot;eyJhbGciOiJSUzI1NiJ9.eyJhdWQiOiJodHRwczovL2lkZW50aXR5dG9vbGtpdC5nb29nbGVhcGlzLmNvbS9nb29nbGUuaWRlbnRpdHkuaWRlbnRpdHl0b29sa2l0LnYxLklkZW50aXR5VG9vbGtpdCIsImNsYWltcyI6eyJvd25lcklkIjoiWnl5ak55WWRFekduIiwiYWRtaW4iOmZhbHNlfSwiZXhwIjoxNTk1Njk3MDk2LCJpYXQiOjE1OTU2OTM0OTYsImlzcyI6ImZpcmViYXNlLWFkbWluc2RrLThva3lsQGNvZGVwZW4tc3RvcmUtcHJvZHVjdGlvbi5pYW0uZ3NlcnZpY2VhY2NvdW50LmNvbSIsInN1YiI6ImZpcmViYXNlLWFkbWluc2RrLThva3lsQGNvZGVwZW4tc3RvcmUtcHJvZHVjdGlvbi5pYW0uZ3NlcnZpY2VhY2NvdW50LmNvbSIsInVpZCI6Ilp5eWpOeSJ9.AB-dXPST6HJM9RtEckk7BaKt0vx8SXEK7HAuwGsS8llfSc6vJ8IJYQj9JkgDimPzZMXA-kVIDJyrYuGo1BY-Pttu4KzHDBlcZZo1yBu377OskijBO91nzMqLUu8pWqrzCXnBfKaFMtalxsmKwrDkk9J8zD_c_43xe21bwsb972EDila6EDW0iVrxELhXol8LYxGmj_NZhrf-hGonl8KBn_7l66eVxgvqXzSNGEOc84KJw0stdyCwf2wu62C0NNCwZvQKfrxOfAZO7kAqhxmI1iNI42b_mHCcirjRWjYWRVv-SlM-GV-s4pRnDuhRXzcu5cf8mVOPHPxWNMoBYZX1tQ&quot;},&quot;__graphql&quot;:{&quot;data&quot;:{&quot;sessionUser&quot;:{&quot;id&quot;:&quot;ZyyjNy&quot;,&quot;name&quot;:&quot;sqr&quot;,&quot;avatar80&quot;:&quot;https://gravatar.com/avatar/696419256777c4e209cecc1eceea5236?d=https%3A%2F%2Fassets.codepen.io%2Finternal%2Favatars%2Fusers%2Fdefault.png&amp;format=auto&amp;height=80&amp;version=0&amp;width=80&quot;,&quot;avatar512&quot;:&quot;https://gravatar.com/avatar/696419256777c4e209cecc1eceea5236?d=https%3A%2F%2Fassets.codepen.io%2Finternal%2Favatars%2Fusers%2Fdefault.png&amp;format=auto&amp;height=512&amp;version=0&amp;width=512&quot;,&quot;canCreatePosts&quot;:true,&quot;currentContext&quot;:{&quot;id&quot;:&quot;ZyyjNy&quot;,&quot;baseUrl&quot;:&quot;/sqr&quot;,&quot;title&quot;:&quot;sqr&quot;,&quot;name&quot;:&quot;sqr&quot;,&quot;avatar80&quot;:&quot;https://gravatar.com/avatar/696419256777c4e209cecc1eceea5236?d=https%3A%2F%2Fassets.codepen.io%2Finternal%2Favatars%2Fusers%2Fdefault.png&amp;format=auto&amp;height=80&amp;version=0&amp;width=80&quot;,&quot;avatar512&quot;:&quot;https://gravatar.com/avatar/696419256777c4e209cecc1eceea5236?d=https%3A%2F%2Fassets.codepen.io%2Finternal%2Favatars%2Fusers%2Fdefault.png&amp;format=auto&amp;height=512&amp;version=0&amp;width=512&quot;,&quot;username&quot;:&quot;sqr&quot;,&quot;contextType&quot;:&quot;USER&quot;,&quot;projectLimitations&quot;:{&quot;projects&quot;:1,&quot;usedProjects&quot;:0,&quot;__typename&quot;:&quot;ProjectLimitations&quot;},&quot;privateByDefault&quot;:false,&quot;__typename&quot;:&quot;User&quot;},&quot;currentTeamId&quot;:null,&quot;baseUrl&quot;:&quot;/sqr&quot;,&quot;username&quot;:&quot;sqr&quot;,&quot;admin&quot;:false,&quot;anon&quot;:false,&quot;pro&quot;:false,&quot;verified&quot;:true,&quot;teams&quot;:[],&quot;permissions&quot;:{&quot;canCreatePrivate&quot;:false,&quot;canUploadAssets&quot;:false,&quot;__typename&quot;:&quot;UserPermissions&quot;},&quot;__typename&quot;:&quot;User&quot;}}},&quot;__boomboom&quot;:{&quot;serve_url&quot;:&quot;https://cdpn.io/boomboom/v2/index.html&quot;,&quot;store_url&quot;:&quot;https://cdpn.io/boomboom/v2/store&quot;},&quot;__editor_config&quot;:{&quot;id&quot;:&quot;classic&quot;,&quot;editors&quot;:[{&quot;id&quot;:&quot;html&quot;,&quot;type&quot;:&quot;html&quot;,&quot;name&quot;:&quot;HTML&quot;,&quot;showEditor&quot;:true,&quot;showSettings&quot;:true,&quot;showProcessors&quot;:true,&quot;embeds&quot;:{&quot;showViewCompiled&quot;:true},&quot;settings&quot;:[{&quot;id&quot;:&quot;processor&quot;,&quot;name&quot;:&quot;HTML Preprocessor&quot;,&quot;type&quot;:&quot;select&quot;,&quot;visible&quot;:true,&quot;values&quot;:[{&quot;id&quot;:&quot;none&quot;,&quot;name&quot;:&quot;None&quot;,&quot;value&quot;:&quot;none&quot;,&quot;default&quot;:true},{&quot;id&quot;:&quot;haml&quot;,&quot;name&quot;:&quot;Haml&quot;,&quot;value&quot;:&quot;haml&quot;},{&quot;id&quot;:&quot;markdown&quot;,&quot;name&quot;:&quot;Markdown&quot;,&quot;value&quot;:&quot;markdown&quot;},{&quot;id&quot;:&quot;slim&quot;,&quot;name&quot;:&quot;Slim&quot;,&quot;value&quot;:&quot;slim&quot;},{&quot;id&quot;:&quot;pug&quot;,&quot;name&quot;:&quot;Pug&quot;,&quot;value&quot;:&quot;pug&quot;}]},{&quot;id&quot;:&quot;html_classes&quot;,&quot;name&quot;:&quot;Add Class(es) to &lt;html&gt;&quot;,&quot;type&quot;:&quot;input&quot;,&quot;placeholder&quot;:&quot;e.g. single post post-1234&quot;,&quot;visible&quot;:true},{&quot;id&quot;:&quot;head&quot;,&quot;name&quot;:&quot;Stuff for &lt;head&gt;&quot;,&quot;type&quot;:&quot;textarea&quot;,&quot;placeholder&quot;:&quot;e.g. &lt;meta&gt;, &lt;link&gt;, &lt;script&gt;&quot;,&quot;visible&quot;:true}],&quot;actions&quot;:[{&quot;id&quot;:&quot;tidy_html&quot;,&quot;type&quot;:&quot;tidy_code&quot;,&quot;name&quot;:&quot;Format HTML&quot;,&quot;disabled_processors&quot;:[&quot;haml&quot;,&quot;slim&quot;]},{&quot;id&quot;:&quot;view_compiled_html&quot;,&quot;type&quot;:&quot;view_compiled&quot;,&quot;name&quot;:&quot;View Compiled HTML&quot;,&quot;disabled_processors&quot;:[&quot;none&quot;],&quot;showInEmbeds&quot;:true},{&quot;id&quot;:&quot;analyze_html&quot;,&quot;type&quot;:&quot;analyze&quot;,&quot;name&quot;:&quot;Analyze HTML&quot;},{&quot;id&quot;:&quot;maximize_html_editor&quot;,&quot;type&quot;:&quot;maximize&quot;,&quot;name&quot;:&quot;Maximize HTML Editor&quot;},{&quot;id&quot;:&quot;minimize_html_editor&quot;,&quot;type&quot;:&quot;minimize&quot;,&quot;name&quot;:&quot;Minimize HTML Editor&quot;},{&quot;id&quot;:&quot;fold_all_html&quot;,&quot;type&quot;:&quot;fold_all&quot;,&quot;name&quot;:&quot;Fold All&quot;},{&quot;id&quot;:&quot;unfold_all_html&quot;,&quot;type&quot;:&quot;unfold_all&quot;,&quot;name&quot;:&quot;Unfold All&quot;}],&quot;processors&quot;:[{&quot;id&quot;:&quot;none&quot;,&quot;name&quot;:&quot;None&quot;},{&quot;id&quot;:&quot;haml&quot;,&quot;name&quot;:&quot;Haml&quot;},{&quot;id&quot;:&quot;markdown&quot;,&quot;name&quot;:&quot;Markdown&quot;},{&quot;id&quot;:&quot;slim&quot;,&quot;name&quot;:&quot;Slim&quot;},{&quot;id&quot;:&quot;pug&quot;,&quot;name&quot;:&quot;Pug&quot;}]},{&quot;id&quot;:&quot;css&quot;,&quot;type&quot;:&quot;css&quot;,&quot;name&quot;:&quot;CSS&quot;,&quot;showEditor&quot;:true,&quot;showSettings&quot;:true,&quot;showProcessors&quot;:true,&quot;showVendorPrefixing&quot;:true,&quot;embeds&quot;:{&quot;showViewCompiled&quot;:true},&quot;actions&quot;:[{&quot;id&quot;:&quot;tidy_css&quot;,&quot;type&quot;:&quot;tidy_code&quot;,&quot;name&quot;:&quot;Format CSS&quot;,&quot;disabled_processors&quot;:[&quot;sass&quot;,&quot;stylus&quot;]},{&quot;id&quot;:&quot;view_compiled_css&quot;,&quot;type&quot;:&quot;view_compiled&quot;,&quot;name&quot;:&quot;View Compiled CSS&quot;,&quot;disabled_processors&quot;:[&quot;none&quot;],&quot;disabled_prefixes&quot;:[&quot;neither&quot;,&quot;prefixfree&quot;]},{&quot;id&quot;:&quot;analyze_css&quot;,&quot;type&quot;:&quot;analyze&quot;,&quot;name&quot;:&quot;Analyze CSS&quot;},{&quot;id&quot;:&quot;maximize_css_editor&quot;,&quot;type&quot;:&quot;maximize&quot;,&quot;name&quot;:&quot;Maximize CSS Editor&quot;},{&quot;id&quot;:&quot;minimize_css_editor&quot;,&quot;type&quot;:&quot;minimize&quot;,&quot;name&quot;:&quot;Minimize CSS Editor&quot;},{&quot;id&quot;:&quot;fold_all_css&quot;,&quot;type&quot;:&quot;fold_all&quot;,&quot;name&quot;:&quot;Fold All&quot;,&quot;disabled_processors&quot;:[&quot;sass&quot;]},{&quot;id&quot;:&quot;unfold_all_css&quot;,&quot;type&quot;:&quot;unfold_all&quot;,&quot;name&quot;:&quot;Unfold All&quot;,&quot;disabled_processors&quot;:[&quot;sass&quot;]}],&quot;processors&quot;:[{&quot;id&quot;:&quot;none&quot;,&quot;name&quot;:&quot;None&quot;},{&quot;id&quot;:&quot;less&quot;,&quot;name&quot;:&quot;Less&quot;},{&quot;id&quot;:&quot;scss&quot;,&quot;name&quot;:&quot;SCSS&quot;},{&quot;id&quot;:&quot;sass&quot;,&quot;name&quot;:&quot;Sass&quot;},{&quot;id&quot;:&quot;stylus&quot;,&quot;name&quot;:&quot;Stylus&quot;},{&quot;id&quot;:&quot;postcss&quot;,&quot;name&quot;:&quot;PostCSS&quot;}],&quot;parSuffixes&quot;:[&quot;less&quot;,&quot;scss&quot;,&quot;sass&quot;,&quot;styl&quot;]},{&quot;id&quot;:&quot;js&quot;,&quot;type&quot;:&quot;js&quot;,&quot;name&quot;:&quot;JS&quot;,&quot;showEditor&quot;:true,&quot;showSettings&quot;:true,&quot;showProcessors&quot;:true,&quot;externalResourcesHidden&quot;:false,&quot;embeds&quot;:{&quot;showViewCompiled&quot;:true},&quot;actions&quot;:[{&quot;id&quot;:&quot;tidy_js&quot;,&quot;type&quot;:&quot;tidy_code&quot;,&quot;name&quot;:&quot;Format JavaScript&quot;,&quot;disabled_processors&quot;:[&quot;coffeescript, livescript&quot;]},{&quot;id&quot;:&quot;view_compiled_js&quot;,&quot;type&quot;:&quot;view_compiled&quot;,&quot;name&quot;:&quot;View Compiled JavaScript&quot;,&quot;disabled_processors&quot;:[&quot;none&quot;]},{&quot;id&quot;:&quot;analyze_js&quot;,&quot;type&quot;:&quot;analyze&quot;,&quot;name&quot;:&quot;Analyze JavaScript&quot;},{&quot;id&quot;:&quot;maximize_js_editor&quot;,&quot;type&quot;:&quot;maximize&quot;,&quot;name&quot;:&quot;Maximize JavaScript Editor&quot;},{&quot;id&quot;:&quot;minimize_js_editor&quot;,&quot;type&quot;:&quot;minimize&quot;,&quot;name&quot;:&quot;Minimize JavaScript Editor&quot;},{&quot;id&quot;:&quot;fold_all_js&quot;,&quot;type&quot;:&quot;fold_all&quot;,&quot;name&quot;:&quot;Fold All&quot;},{&quot;id&quot;:&quot;unfold_all_js&quot;,&quot;type&quot;:&quot;unfold_all&quot;,&quot;name&quot;:&quot;Unfold All&quot;}],&quot;processors&quot;:[{&quot;id&quot;:&quot;none&quot;,&quot;name&quot;:&quot;None&quot;},{&quot;id&quot;:&quot;babel&quot;,&quot;name&quot;:&quot;Babel&quot;},{&quot;id&quot;:&quot;typescript&quot;,&quot;name&quot;:&quot;TypeScript&quot;},{&quot;id&quot;:&quot;coffeescript&quot;,&quot;name&quot;:&quot;CoffeeScript&quot;},{&quot;id&quot;:&quot;livescript&quot;,&quot;name&quot;:&quot;LiveScript&quot;}]}],&quot;formatters&quot;:[{&quot;id&quot;:&quot;classic&quot;,&quot;name&quot;:&quot;Classic&quot;,&quot;runOn&quot;:[{&quot;eventType&quot;:&quot;demand&quot;}],&quot;url&quot;:&quot;https://fi593g2v2a.execute-api.us-west-2.amazonaws.com/production/format&quot;}],&quot;layout&quot;:{&quot;default&quot;:&quot;top&quot;},&quot;linters&quot;:[{&quot;id&quot;:&quot;classic&quot;,&quot;name&quot;:&quot;Classic&quot;,&quot;runOn&quot;:[{&quot;eventType&quot;:&quot;demand&quot;}],&quot;url&quot;:&quot;https://fi593g2v2a.execute-api.us-west-2.amazonaws.com/production/lint&quot;}],&quot;preview&quot;:{&quot;intervalMaxWaitMS&quot;:3500,&quot;intervalMS&quot;:1200},&quot;settings&quot;:[{&quot;id&quot;:&quot;behavior&quot;,&quot;name&quot;:&quot;Behavior&quot;,&quot;type&quot;:&quot;setting&quot;},{&quot;id&quot;:&quot;editor&quot;,&quot;name&quot;:&quot;Editor&quot;,&quot;type&quot;:&quot;setting&quot;}]},&quot;__export_service_url&quot;:&quot;https://codepen.io/api/export&quot;,&quot;__item&quot;:&quot;{\&quot;dependencies\&quot;:{},\&quot;editor_settings\&quot;:{\&quot;auto_run\&quot;:true,\&quot;autocomplete\&quot;:false,\&quot;code_folding\&quot;:true,\&quot;css_pre_processor\&quot;:\&quot;none\&quot;,\&quot;css_prefix\&quot;:\&quot;neither\&quot;,\&quot;css_starter\&quot;:\&quot;neither\&quot;,\&quot;emmet_active\&quot;:true,\&quot;font_size\&quot;:\&quot;14\&quot;,\&quot;font_type\&quot;:\&quot;monaco\&quot;,\&quot;format_on_save\&quot;:false,\&quot;html_pre_processor\&quot;:\&quot;none\&quot;,\&quot;indent_with\&quot;:\&quot;spaces\&quot;,\&quot;js_pre_processor\&quot;:\&quot;none\&quot;,\&quot;key_bindings\&quot;:\&quot;normal\&quot;,\&quot;line_numbers\&quot;:true,\&quot;line_wrapping\&quot;:true,\&quot;match_brackets\&quot;:true,\&quot;snippets\&quot;:{\&quot;markupSnippets\&quot;:{},\&quot;stylesheetSnippets\&quot;:{}},\&quot;tab_size\&quot;:\&quot;2\&quot;,\&quot;theme\&quot;:\&quot;twilight\&quot;,\&quot;id\&quot;:\&quot;ZoQRoz\&quot;,\&quot;auto_save\&quot;:true},\&quot;hashid\&quot;:\&quot;ZoQRoz\&quot;,\&quot;itemType\&quot;:\&quot;pen\&quot;,\&quot;owner_id\&quot;:\&quot;pnEaYKYdEzGn\&quot;,\&quot;resources\&quot;:[],\&quot;tags\&quot;:[],\&quot;id\&quot;:23921634,\&quot;user_id\&quot;:1493964,\&quot;html\&quot;:\&quot;&lt;section id=\\\&quot;blog\\\&quot; class=\\\&quot;blog\\\&quot;&gt;\\n  &lt;div class=\\\&quot;blog__header\\\&quot;&gt;\\n    &lt;p class=\\\&quot;blog__header1\\\&quot;&gt;some of my&lt;/p&gt;\\n    &lt;h2 class=\\\&quot;blog__header2\\\&quot;&gt;Medium\\n      &lt;span class=\\\&quot;blog__header2Span\\\&quot;&gt;posts&lt;/span&gt;\\n    &lt;/h2&gt;\\n  &lt;/div&gt;\\n  &lt;ul class=\\\&quot;blog__slider\\\&quot;&gt;\\n    Posts go here\\n  &lt;/ul&gt;\\n  &lt;ul class=\\\&quot;blog__counter\\\&quot;&gt;\\n    &lt;li class=\\\&quot;blog__counterItem blog__counterItem-active\\\&quot;&gt;&lt;/li&gt;\\n    &lt;li class=\\\&quot;blog__counterItem\\\&quot;&gt;&lt;/li&gt;\\n    &lt;li class=\\\&quot;blog__counterItem\\\&quot;&gt;&lt;/li&gt;\\n  &lt;/ul&gt;\\n&lt;/section&gt;\&quot;,\&quot;css\&quot;:\&quot;a{\\n  color: inherit;\\n  text-decoration: none;\\n}\\nul{\\n   list-style: none;\\n}\\n\\n.blog{\\n   margin: 3rem 1rem;\\n   display: flex;\\n   flex-direction: column;\\n   justify-content: center;\\n   align-items: center;\\n   &amp;__header{\\n      text-align: center;\\n   }\\n   &amp;__header1{\\n      margin: 0;\\n      font-size: 1.1rem;\\n      font-weight: 300;\\n      letter-spacing: .2px;\\n      text-transform: uppercase;\\n   }\\n   &amp;__header2{\\n      margin-top: .3rem;\\n      font-size: 1.4rem;\\n      font-weight: 500;\\n   }\\n   &amp;__header2Span{\\n      font-weight: 400;\\n      font-size: 1.25rem;\\n   }\\n   &amp;__slider{\\n      padding: 0;\\n      display: flex;\\n      flex-direction: row;\\n      justify-content: center\\n   }\\n   &amp;__post{\\n      margin: 3rem 1rem;\\n      width: 25%;\\n      -webkit-box-shadow: 9px 9px 20px 0px rgba(0,0,0, .4);\\n      -moz-box-shadow: 9px 9px 20px 0px rgba(0,0,0, .4);\\n      box-shadow: 9px 9px 20px 0px rgba(0,0,0, .4);\\n   }\\n   &amp;__topImg{\\n      max-width: 100%;\\n   }\\n   &amp;__content{\\n      padding: .8rem;\\n   }\\n   &amp;__preview{\\n      font-size: .95rem;\\n      font-weight: 300;\\n   }\\n   &amp;__title{\\n      margin-top: 0;\\n      font-size: 1.4rem;\\n   }\\n   &amp;__intro{\\n      line-height: 1.5;\\n   }\\n   &amp;__info{\\n      font-weight: 300;\\n   }\\n   &amp;__author{\\n      font-size: .9rem;\\n   }\\n   &amp;__date{\\n      font-size: .85rem;\\n   }\\n\\n   &amp;__counter{\\n      margin: 0;\\n      padding: 0;\\n      display: flex;\\n      flex-direction: row;\\n   }\\n   &amp;__counterItem{\\n      height: 20px;\\n      width: 20px;\\n      margin: .5rem;\\n      background-color: lightgray;\\n      border: 1px solid lightgray;\\n      border-radius: 25px;\\n      &amp;:hover{\\n         cursor: pointer;\\n      }\\n   }\\n   &amp;__counterItem-active{\\n      border: 1px solid lightblue;\\n      background-color: lightblue;\\n   }\\n}\\n\&quot;,\&quot;parent\&quot;:0,\&quot;js\&quot;:\&quot;fetch(&#39;https://api.rss2json.com/v1/api.json?rss_url=https://medium.com/feed/@KonradDaWo&#39;)\\n   .then((res) =&gt; res.json())\\n   .then((data) =&gt; {\\n      // Filter for acctual posts. Comments don&#39;t have categories, therefore can filter for items with categories bigger than 0\\n      const res = data.items //This is an array with the content. No feed, no info about author etc..\\n      const posts = res.filter(item =&gt; item.categories.length &gt; 0) // That&#39;s the main trick* !\\n\\n      // Functions to create a short text out of whole blog&#39;s content\\n      function toText(node) {\\n         let tag = document.createElement(&#39;div&#39;)\\n         tag.innerHTML = node\\n         node = tag.innerText\\n         return node\\n      }\\n      function shortenText(text,startingPoint ,maxLength) {\\n         return text.length &gt; maxLength?\\n         text.slice(startingPoint, maxLength):\\n         text\\n      }\\n\\n      // Put things in right spots of markup\\n      let output = &#39;&#39;;\\n      posts.forEach((item) =&gt; {\\n         output += `\\n         &lt;li class=\\\&quot;blog__post\\\&quot;&gt;\\n            &lt;a href=\\\&quot;${item.link}\\\&quot;&gt;\\n               &lt;img src=\\\&quot;${item.thumbnail}\\\&quot; class=\\\&quot;blog__topImg\\\&quot;&gt;&lt;/img&gt;\\n               &lt;div class=\\\&quot;blog__content\\\&quot;&gt;\\n                  &lt;div class=\\\&quot;blog_preview\\\&quot;&gt;\\n                     &lt;h2 class=\\\&quot;blog__title\\\&quot;&gt;${shortenText(item.title, 0, 30)+ &#39;...&#39;}&lt;/h2&gt;\\n                     &lt;p class=\\\&quot;blog__intro\\\&quot;&gt;${&#39;...&#39; + shortenText(toText(item.content),60, 300)+ &#39;...&#39;}&lt;/p&gt;\\n                  &lt;/div&gt;\\n                  &lt;hr&gt;\\n                  &lt;div class=\\\&quot;blog__info\\\&quot;&gt;\\n                     &lt;span class=\\\&quot;blog__author\\\&quot;&gt;${item.author}&lt;/span&gt;\\n                     &lt;span class=\\\&quot;blog__date\\\&quot;&gt;${shortenText(item.pubDate,0 ,10)}&lt;/span&gt;\\n                  &lt;/div&gt;\\n               &lt;/div&gt;\\n            &lt;a/&gt;\\n         &lt;/li&gt;`\\n\\n      })\\n      document.querySelector(&#39;.blog__slider&#39;).innerHTML = output\\n})\\n\\n\&quot;,\&quot;html_pre_processor\&quot;:\&quot;none\&quot;,\&quot;css_pre_processor\&quot;:\&quot;scss\&quot;,\&quot;js_pre_processor\&quot;:\&quot;none\&quot;,\&quot;html_classes\&quot;:\&quot;\&quot;,\&quot;css_starter\&quot;:\&quot;neither\&quot;,\&quot;css_prefix_free\&quot;:null,\&quot;css_external\&quot;:null,\&quot;js_library\&quot;:null,\&quot;js_modernizr\&quot;:null,\&quot;js_external\&quot;:null,\&quot;created_at\&quot;:\&quot;2018-04-23T19:04:50.000Z\&quot;,\&quot;updated_at\&quot;:\&quot;2018-04-23T19:10:59.000Z\&quot;,\&quot;session_hash\&quot;:\&quot;df9104b3897ad41f88b9bf4f1521c4cc\&quot;,\&quot;title\&quot;:\&quot;Medium API, blog posts from Medium \&quot;,\&quot;description\&quot;:\&quot;\&quot;,\&quot;slug_hash\&quot;:\&quot;ZoQRoz\&quot;,\&quot;head\&quot;:\&quot;\&quot;,\&quot;private\&quot;:false,\&quot;has_animation\&quot;:false,\&quot;css_pre_processor_lib\&quot;:\&quot;\&quot;,\&quot;checksum\&quot;:0,\&quot;screenshot_uuid\&quot;:\&quot;488ff2a1-29b7-4cd1-bbe4-ef12cf4aa473\&quot;,\&quot;team_id\&quot;:0,\&quot;css_prefix\&quot;:\&quot;neither\&quot;,\&quot;template\&quot;:false,\&quot;js_module\&quot;:false,\&quot;pen_hash\&quot;:null}&quot;,&quot;__jwt&quot;:&quot;eyJhbGciOiJIUzI1NiJ9.eyJkYXRhIjp7InBhaWQiOmZhbHNlLCJ0ZWFtX2lkIjoiWWRFekduIiwidXNlcl9pZCI6Ilp5eWpOeSIsInVzZXJuYW1lIjoic3FyIn0sImV4cCI6MTU5NTc3OTg5Nn0.moNe1mQodx75x0--ElU2MyNsYNy7WCLGVx-mSKSuuik&quot;,&quot;__layoutType&quot;:null,&quot;__packages_domain&quot;:&quot;https://bundles-development.cdpn.io&quot;,&quot;__packages_enabled&quot;:false,&quot;__pageType&quot;:&quot;pen&quot;,&quot;__preprocessors_url&quot;:&quot;https://wfwf9k3tn7.execute-api.us-west-2.amazonaws.com/production&quot;,&quot;__profiled&quot;:{&quot;base_url&quot;:&quot;/Konrad29&quot;,&quot;hashid&quot;:&quot;pnEaYK&quot;,&quot;id&quot;:1493964,&quot;name&quot;:&quot;Konrad29&quot;,&quot;type&quot;:&quot;user&quot;,&quot;username&quot;:&quot;Konrad29&quot;},&quot;__rtData&quot;:&quot;{\&quot;maxMembers\&quot;:0,\&quot;roomID\&quot;:\&quot;ZoQRoz/live\&quot;,\&quot;roomType\&quot;:\&quot;live\&quot;,\&quot;updatedAt\&quot;:1524510659,\&quot;user\&quot;:{\&quot;id\&quot;:\&quot;ZyyjNy\&quot;,\&quot;hashid\&quot;:\&quot;ZyyjNy\&quot;,\&quot;name\&quot;:\&quot;sqr\&quot;,\&quot;username\&quot;:\&quot;sqr\&quot;,\&quot;role\&quot;:\&quot;editor\&quot;}}&quot;,&quot;__embed_modal_script&quot;:&quot;https://static.codepen.io/assets/embed/modal/embed_modal-707400f485648c102f2a410a60705b4996f3ab4bc2338b88c83dcfa330f944c9.js&quot;,&quot;__run_mode_script&quot;:&quot;https://static.codepen.io/assets/libs/codemirror/addon/runmode/runmode-bfc439c2e56cc8aa5b0ed0c95c742d64b92d6ec36eb562d881bfefcb020bf614.js&quot;,&quot;__runtime_js&quot;:&quot;https://static.codepen.io/assets/common/runtime-78f7737f2b92b1b279253c92344b93db2bdf0e3193c90dae7d462d102b33c722.js&quot;,&quot;__standalone_run_mode_script&quot;:&quot;https://static.codepen.io/assets/libs/codemirror/addon/runmode/runmode-standalone-86ed18f2f4ca933889b656c3dcd4135af20477c88c764ae92dd139b682a0ab98.js&quot;,&quot;__syntax_highlighting_script&quot;:&quot;https://static.codepen.io/assets/comments/syntax_highlight_comments.js&quot;,&quot;__eijs&quot;:&quot;https://static.codepen.io/assets/embed/ei.js&quot;,&quot;__favicon_mask_icon&quot;:&quot;https://static.codepen.io/assets/favicon/logo-pin-8f3771b1072e3c38bd662872f6b673a722f4b3ca2421637d5596661b4e2132cc.svg&quot;,&quot;__favicon_shortcut_icon&quot;:&quot;https://static.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico&quot;,&quot;__path_to_iframe_console_runner&quot;:&quot;https://static.codepen.io/assets/editor/iframe/iframeConsoleRunner-dc0d50e60903d6825042d06159a8d5ac69a6c0e9bcef91e3380b17617061ce0f.js&quot;,&quot;__path_to_iframe_refresh_css&quot;:&quot;https://static.codepen.io/assets/editor/iframe/iframeRefreshCSS-e03f509ba0a671350b4b363ff105b2eb009850f34a2b4deaadaa63ed5d970b37.js&quot;,&quot;__path_to_iframe_runtime_errors&quot;:&quot;https://static.codepen.io/assets/editor/iframe/iframeRuntimeErrors-29f059e28a3c6d3878960591ef98b1e303c1fe1935197dae7797c017a3ca1e82.js&quot;,&quot;__path_to_processor_worker&quot;:&quot;https://static.codepen.io/assets/packs/router.js&quot;,&quot;__path_to_stop_execution_on_timeout&quot;:&quot;https://static.codepen.io/assets/common/stopExecutionOnTimeout-157cd5b220a5c80d4ff8e0e70ac069bffd87a61252088146915e8726e5d9f147.js&quot;,&quot;__path_to_webpack_runtime&quot;:&quot;https://static.codepen.io/assets/common/runtime-78f7737f2b92b1b279253c92344b93db2bdf0e3193c90dae7d462d102b33c722.js&quot;,&quot;__pen_normalize_css_url&quot;:&quot;https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css&quot;,&quot;__pen_prefix_free_url&quot;:&quot;https://cdnjs.cloudflare.com/ajax/libs/prefixfree/1.0.7/prefixfree.min.js&quot;,&quot;__pen_reset_css_url&quot;:&quot;https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css&quot;,&quot;__cdn_css_url&quot;:&quot;https://static.codepen.io/assets/editor/other/cdn/cdncss_data-3920a09dad6d4fc8f26388543dd6e897701bb9eb7adad7644001579fa97c3bcc.json&quot;,&quot;__cdn_js_url&quot;:&quot;https://static.codepen.io/assets/editor/other/cdn/cdnjs_data-d48ecfb6f69488f4fd036843964b79819dab4f33a0ef800d8e3362688252e672.json&quot;,&quot;__theme_url_twilight&quot;:&quot;https://static.codepen.io/assets/editor/themes/twilight-bbb3d58f8024c27567f788f3990f2dce8754c2b67246bf12ad766768fe51955b.css&quot;,&quot;__theme_url_solarized_dark&quot;:&quot;https://static.codepen.io/assets/editor/themes/solarized-dark-74aa4885fce5e2654a252ce5d046a231528fa7d0bab4a6da9335f61f75641a24.css&quot;,&quot;__theme_url_tomorrow_night&quot;:&quot;https://static.codepen.io/assets/editor/themes/tomorrow-night-d40615974321d1e903d870a0feb427a925a3aaa6710a856a012cb5feb317de06.css&quot;,&quot;__theme_url_oceanic_dark&quot;:&quot;https://static.codepen.io/assets/editor/themes/oceanic-dark-6819a04bdb142273008450549c44fae26e7e75bc5e8ca6d8a78d3bdca2e14057.css&quot;,&quot;__theme_url_panda&quot;:&quot;https://static.codepen.io/assets/editor/themes/panda-00401281f2fb82904fcc5bdf9ccdade7866b7674181a06b0f26ee6fc591aed29.css&quot;,&quot;__theme_url_duotone_dark&quot;:&quot;https://static.codepen.io/assets/editor/themes/duotone-dark-6f36080c52f085d1c4b7aa50e7eeb8e9bae96206fa22c6aa4e536db129ed7f47.css&quot;,&quot;__theme_url_highcontrast_dark&quot;:&quot;https://static.codepen.io/assets/editor/themes/highcontrast-dark-6fac7534892153b41a69be61dcfbd27dacbe6f3359e73912fea94614a283be8e.css&quot;,&quot;__theme_url_classic&quot;:&quot;https://static.codepen.io/assets/editor/themes/classic-d7cab86e6d3da60d8cc880622136b2b12354fcb6d74dbf8fa7344b4e2c8c7a07.css&quot;,&quot;__theme_url_solarized_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/solarized-light-5e319a816752c9f0b7caed1d6d7ef1c46dd9b4a6c880aae4330e995a66da8740.css&quot;,&quot;__theme_url_xq_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/xq-light-ff587a13ad3689cf47ce4efaeef9ba5a4693ca8f8b7cdc795207f5cbcefa93fc.css&quot;,&quot;__theme_url_oceanic_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/oceanic-light-7bc150e27e7d7bd775ee1f1a6ee5a77e6fbe19cbeacf078ccb4023ae81c0f834.css&quot;,&quot;__theme_url_mdn_like&quot;:&quot;https://static.codepen.io/assets/editor/themes/mdn-like-b6d8af50e237d6feac2a7c152f479999705d5a33e6a9512f6ce366cc77979855.css&quot;,&quot;__theme_url_duotone_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/duotone-light-3c888339133e6ccf10476b8000003491cc4cf6d09c84a49ba1d60b678544e358.css&quot;,&quot;__theme_url_highcontrast_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/highcontrast-light-48ad69bb14f1618e8908352ea7101f66afecd53f3fd15002116f1e232ce43125.css&quot;,&quot;__theme_url_scoped_twilight&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/twilight-440b9df51ecbe6257384600a5ea09c8ac33a9d860e15d950190a11d4f82f7909.css&quot;,&quot;__theme_url_scoped_solarized_dark&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/solarized-dark-4b456e5e71195d8d9c8e5f060722d5f9fb908be40147ff5159851a72051f3747.css&quot;,&quot;__theme_url_scoped_tomorrow_night&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/tomorrow-night-8b26461b91055f2cd4c7bebebb26b97807e33048c46f80d53d4ade465fe11c71.css&quot;,&quot;__theme_url_scoped_oceanic_dark&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/oceanic-dark-a36b8ac5408ac81f9dea080ce5fb9ddd71537448b2c20f46e5145fb96ed1db62.css&quot;,&quot;__theme_url_scoped_panda&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/panda-16542061ba4c8158eef01aaa0bc82eda10310b37aa85985e27eb6d49f44b34ea.css&quot;,&quot;__theme_url_scoped_duotone_dark&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/duotone-dark-f8ac6d0ba133460720598e2476004dae25eb6dc631e181b558555ed4a1c62b9e.css&quot;,&quot;__theme_url_scoped_highcontrast_dark&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/highcontrast-dark-1f760b46f811648ea7a58a89f7d3b174b3c2733fa00ab78dc56b81fcd27ae137.css&quot;,&quot;__theme_url_scoped_classic&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/classic-e4128896151af1d515c6553eaeb67043bb53a354c2e49a25ed2b25de526710da.css&quot;,&quot;__theme_url_scoped_solarized_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/solarized-light-2527ff5d4dbff7c38a474d4dfab0a39a303cddb0fb64daccb85303533c5f99fc.css&quot;,&quot;__theme_url_scoped_xq_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/xq-light-5d0c8647757fcd697ee1c1f5d39edb372193e87bb402d0d4a9866d87cdc089ab.css&quot;,&quot;__theme_url_scoped_oceanic_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/oceanic-light-df8f48b79b5c783af47cf585b78a9b06801b89754ddfd18ed48e0af50fb09d80.css&quot;,&quot;__theme_url_scoped_mdn_like&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/mdn-like-e3435649da66454bfb7a84146034426aee6a1ed661170537eb120108125109b4.css&quot;,&quot;__theme_url_scoped_duotone_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/duotone-light-44c77e7ad84a7326ec3c070c6a2e30bc81677da2cb8752683499eb9ae659073b.css&quot;,&quot;__theme_url_scoped_highcontrast_light&quot;:&quot;https://static.codepen.io/assets/editor/themes/scoped/highcontrast-light-001750c2a4a8eaba783e4bd98b0df57d07a9ca269377ce161d1c54e12a5a66ff.css&quot;}">
<script src="https://static.codepen.io/assets/common/browser_support-1963aa6406ae47d3176af996336c5d219acd8913c5af309e72f18933e95201cc.js"></script>
<script src="https://static.codepen.io/assets/common/everypage-a63f0cbd5f67116206c89108a0a1da6978ab1606d953812d875b800cf8fe823e.js"></script>
<script src="https://fast.appcues.com/69186.js"></script>
<script src="https://static.codepen.io/assets/common/analytics_and_notifications-538ab2710674d4676fe331ffda620410176f9ac968498eeba639b3f0d1125ff8.js"></script>
<script>
LUX=(function(){var a=("undefined"!==typeof(LUX)&&"undefined"!==typeof(LUX.gaMarks)?LUX.gaMarks:[]);var d=("undefined"!==typeof(LUX)&&"undefined"!==typeof(LUX.gaMeasures)?LUX.gaMeasures:[]);var j="LUX_start";var k=window.performance;var l=("undefined"!==typeof(LUX)&&LUX.ns?LUX.ns:(Date.now?Date.now():+(new Date())));if(k&&k.timing&&k.timing.navigationStart){l=k.timing.navigationStart}function f(){if(k&&k.now){return k.now()}var o=Date.now?Date.now():+(new Date());return o-l}function b(n){if(k){if(k.mark){return k.mark(n)}else{if(k.webkitMark){return k.webkitMark(n)}}}a.push({name:n,entryType:"mark",startTime:f(),duration:0});return}function m(p,t,n){if("undefined"===typeof(t)&&h(j)){t=j}if(k){if(k.measure){if(t){if(n){return k.measure(p,t,n)}else{return k.measure(p,t)}}else{return k.measure(p)}}else{if(k.webkitMeasure){return k.webkitMeasure(p,t,n)}}}var r=0,o=f();if(t){var s=h(t);if(s){r=s.startTime}else{if(k&&k.timing&&k.timing[t]){r=k.timing[t]-k.timing.navigationStart}else{return}}}if(n){var q=h(n);if(q){o=q.startTime}else{if(k&&k.timing&&k.timing[n]){o=k.timing[n]-k.timing.navigationStart}else{return}}}d.push({name:p,entryType:"measure",startTime:r,duration:(o-r)});return}function h(n){return c(n,g())}function c(p,o){for(i=o.length-1;i>=0;i--){var n=o[i];if(p===n.name){return n}}return undefined}function g(){if(k){if(k.getEntriesByType){return k.getEntriesByType("mark")}else{if(k.webkitGetEntriesByType){return k.webkitGetEntriesByType("mark")}}}return a}return{mark:b,measure:m,gaMarks:a,gaMeasures:d}})();LUX.ns=(Date.now?Date.now():+(new Date()));LUX.ac=[];LUX.cmd=function(a){LUX.ac.push(a)};LUX.init=function(){LUX.cmd(["init"])};LUX.send=function(){LUX.cmd(["send"])};LUX.addData=function(a,b){LUX.cmd(["addData",a,b])};LUX_ae=[];window.addEventListener("error",function(a){LUX_ae.push(a)});LUX_al=[];if("function"===typeof(PerformanceObserver)&&"function"===typeof(PerformanceLongTaskTiming)){var LongTaskObserver=new PerformanceObserver(function(c){var b=c.getEntries();for(var a=0;a<b.length;a++){var d=b[a];LUX_al.push(d)}});try{LongTaskObserver.observe({type:["longtask"]})}catch(e){}};
</script>
<script src="https://cdn.speedcurve.com/js/lux.js?id=410041" async defer crossorigin="anonymous"></script>
<script src="https://static.codepen.io/assets/packs/js/vendor-914018091c1d46156ec7.chunk.js"></script>
<script src="https://static.codepen.io/assets/packs/js/2-15fe8a2e429c51530a1d.chunk.js"></script>
<script src="https://static.codepen.io/assets/packs/js/everypage-01e4a3462b1cea7352c1.js"></script>
<script src="https://static.codepen.io/assets/packs/js/vendor-914018091c1d46156ec7.chunk.js"></script>
<script src="https://static.codepen.io/assets/packs/js/firebaseConnectLibs-d22f9c9bbb3d59100a2f.js"></script>
<script src="https://static.codepen.io/assets/packs/js/processorRouter-3e75751bdd181a7aeb8a.js"></script>
<script src="https://static.filestackapi.com/filestack-js/3.x.x/filestack.min.js"></script>
<script src="https://static.codepen.io/assets/editor/global/commonLibs-9baf61da2f0b1adbfdbda1a98aa009379eddc23641e45edf6d5c41f98fe361d0.js"></script>
<script src="https://static.codepen.io/assets/editor/global/codemirror-c4c6f5379377e67f3e79161513066c5c491a47a393cd3e5669c9d3f40cee44fe.js"></script>
<script src="https://static.codepen.io/assets/libs/emmet-codemirror-plugin-4eb895d546572aaa83c328e8766ad12bff808dc4115466de4baab2f025c13b6a.js"></script>
<script src="https://static.codepen.io/assets/editor/pen/index-2df22849eceb879934d800c6de7c19ce05b33ad5db974ef8fa72288f3d5d6794.js"></script>
</body>
</html>

# Glitch

Glitch is a helper bookmarklet that helps run accessibility tests and contains other helpful tools<br>
[Glitch](javascript: (function() {var _i = function(s, data_id, cb) {var sc = document.createElement('script');sc.setAttribute('data-id', data_id);sc.onload = function() {sc.onload = null;sc.onreadystatechange = null;cb.call(this);};sc.onreadystatechange = function() {if (/^(complete|loaded)$/.test(this.readyState) === true) {sc.onreadystatechange = null;sc.onload();}};sc.src = s;if (document.head) { document.head.appendChild(sc); } else { document.getElementsByTagName('head')[0].appendChild(sc); }};glitch = undefined;var bookmarklet_nodes_to_delete = document.querySelectorAll('[data-id='glitch'], [data-id='bookmarklet-css'], [data-id='html-validation']');bookmarklet_nodes_to_delete.forEach((node) => {node.remove();});_i('https://warrenshea.github.io/glitch/app.js', 'glitch', function() {});})();)

## Prerequisites

Gulp 4
NodeJS 12

## Run Development Environment

gulp

## Compile Production Environment to _dist

gulp --prod

## Contributors

Warren Shea

[warrenshea.com](http://www.warrenshea.com)

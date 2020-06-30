<!DOCTYPE html>
<html>
 <head>
   <link rel="import" href="https://prnt.sc/aa0043">
  </head>
<body>

<h1>prnt.sc navigator</h1>

<iframe src="https://prnt.sc/aa0043" title="PRNT.SC">
</iframe>

  <script>
    var link = document.querySelector('link[rel="import"]');
    var content = link.import;

    // Grab DOM from warning.html's document.
    var el = content.querySelector('.under-image');

    document.body.appendChild(el.cloneNode(true));
  </script>
</body>
</html>

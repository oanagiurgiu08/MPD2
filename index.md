
<script>
  document.cookie = "session=test GDPR"; document.cookie = "favorite_task=collect Data"; function alertCookie() { alert(document.cookie); } 
</script>
<body>
  Bine ai venit la laborator.
<button onclick="alertCookie()">Show cookies</button>
<button onclick="clearOutputCookies()">Clear</button>

<div>
  <code id="cookies"></code>
</div>
</body>

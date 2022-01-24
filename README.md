# douphp
XSS vulnerability exists in douphp background adding articles.

Official demo site, administrator login.
https://demo.douphp.com/admin/login.php

Source download address.
https://down.douphp.com/DouPHP_1.6_Release_20220121.zip


Log in to the background and add articles.
![image](1.png)

Insert XSS code at the article name,Submit.
<script>alert(document.cookie)</script>
![image](2.png)

Cookie pops up in the background.
![image](3.png)

The foreground will also trigger vulnerabilities.
![image](4.png)

1. sign up for captcha api: https://www.google.com/recaptcha/admin#list
2. get api code and secret code
3. whitelist your domain in the google
4. update configs.php with your email addresses
5. add api code into the form and secret into configs.php

head
<script src='https://www.google.com/recaptcha/api.js'></script>


footer

<script src="contactme/js/contactme-config.js"></script>
<script src="contactme/js/contactme-1.3.js"></script>
<!-- To enable Google reCAPTCHA, uncomment the next line: -->
<script src="https://www.google.com/recaptcha/api.js?onload=initRecaptchas&render=explicit" async defer></script>   

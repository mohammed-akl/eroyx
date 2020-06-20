---
layout: page
title: Contact
permalink: /contact
comments: false
lang_selector: false
---

<form action="{{site.baseurl}}/message-send" method="POST" netlify>    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control contact" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control contact" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3 contact" name="message" placeholder="Message*" required></textarea>    
<input class="btn gradient-bg margin-15px white-text ftr-btn" type="submit" value="Send">
</form>

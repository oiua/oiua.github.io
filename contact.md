---
layout: page
title: Contact
permalink: /contact/
---
<p id="thanks" style="display:none">Your message has been send successfully. Thank you.</p>
<p id="note">We are happy to hear from you. Please not contact us for advertisement of any form.</p>

<form action="https://www.formingo.co/submit/7091750b-330c-4508-901b-560f168e6b06"
  method="POST" id="form">
  <input type="hidden" name="__redirect" value="{{ site.url }}/contact#thank-you">
	<div style="margin-bottom:15px;">
		<label style="display: inline-block;max-width: 100%;margin-bottom: 5px;font-weight: 700;">
			Name
		</label>
		<input name="name" style="display:block;width:95%;height:34px;padding:6px 12px;font-size:14px; color:#555;background-color:#fff; border:1px solid #ccc;" required="">
	</div>

	<div style="margin-bottom:15px;">
  <label style="display: inline-block;max-width: 100%;margin-bottom: 5px;font-weight: 700;">
			Email
		</label>
		<input name="__replyto" type="email" style="display:block;width:95%;height:34px;padding:6px 12px;font-size:14px; color:#555;background-color:#fff; border:1px solid #ccc;" required="">
	</div>
	<div style="margin-bottom:15px;">
  <label style="display: inline-block;max-width: 100%;margin-bottom: 5px;font-weight: 700;">
			Message
		</label>
		<textarea style="height:100px;display:block;width:95%;padding:6px 12px;font-size:14px; color:#555;background-color:#fff; border:1px solid #ccc;" name="message" required=""></textarea>
	</div>
  <input type="submit" value="Send" style="display:block;margin:0 5px 5px 0;padding: 10px 16px;
    font-size:18px;line-height:1.333;border-radius:6px;color:#FFF;
    background: rgba(0,0,0,.3); border: 1px solid transparent;">
</form>

<script type="text/javascript">
window.onload = function() {
    if (window.location.hash) {
      document.getElementById('thanks').style.display = 'block';
      document.getElementById('form').style.display = 'none';
      document.getElementById('note').style.display = 'none';
    }
};
</script>

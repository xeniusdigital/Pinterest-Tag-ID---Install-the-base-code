# Pinterest-Tag-ID---Install-the-base-code

Add the base code to any page where you want to track conversions. If you want to use retargeting, add this code to every page of your site to create audiences to retarget later.
Be sure to put the base code between the <head> and </head> tags in your HTML document. It should only appear once on a single page, and before the subsequent event code.
Use Enhanced Match to get improved visibility into your conversion data—passing back email data on a conversion lets us better attribute it to an event on Pinterest. To use Enhanced Match, pass back the converting user’s email (or the SHA256 hash of their email) in the em parameter highlighted in blue.

##PinterestTag

<!-- Pinterest Tag -->
<script>
!function(e){if(!window.pintrk){window.pintrk = function () {
window.pintrk.queue.push(Array.prototype.slice.call(arguments))};var
  n=window.pintrk;n.queue=[],n.version="3.0";var
  t=document.createElement("script");t.async=!0,t.src=e;var
  r=document.getElementsByTagName("script")[0];
  r.parentNode.insertBefore(t,r)}}("https://s.pinimg.com/ct/core.js");
pintrk('load', '2613336397798', {em: '<user_email_address>'});
pintrk('page');
</script>
<noscript>
<img height="1" width="1" style="display:none;" alt=""
  src="https://ct.pinterest.com/v3/?event=init&tid=2613336397798&pd[em]=<hashed_email_address>&noscript=1" />
</noscript>
<!-- end Pinterest Tag -->

  
  ##Pinterest Events Codes
  
  https://help.pinterest.com/en/business/article/add-event-codes
  
  
  

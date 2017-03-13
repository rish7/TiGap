TiGap
--------------
Titanium ACS API from PhoneGap Application (only index.html)

![APPC ACS in Phone Gap](http://shareourideas.com/wp-content/uploads/2012/07/ui-in-phonegap.png)
1) First Login to Titanium Colud and Create ACS app
2) Copy Oauth Consumer key and Secret Key or App Key
3) Make Sure your added cocoafish js file. http://sdk.cocoafish.com/js/cocoafish-1.2.min.js . In my application I used jQuery mobile.

4) Then Start code Set data and call
		sdk.sendRequest(ACTION, METHOD, DATA, CALLBACK_FUNCTION);
E.g:- sdk.sendRequest('users/create.json', 'POST', data, callback);
5) You can also manage users in ACS web dashboard.

Check more details here


http://shareourideas.com/2012/07/04/titanium-acs-api-in-phonegap/


# Zoho D7 Custom SMS Deluge 
# D7 Networks provides powerful messaging APIs for SMS

This function sends SMS using D7 Networks directly from Zoho CRM Leads via Deluge.  
It:
- Fetches mobile number from a Lead.
- Prepares message and cleans the number.
- Sends SMS using D7 API.
- Logs the message in a custom `d7sms__D7SMS` module with details.

You must configure these org variables in Zoho CRM:
- `d7sms__D7API_Token`
- `d7sms__from`
- `d7sms__apifunctionurl`

Customize the message as needed in the script.

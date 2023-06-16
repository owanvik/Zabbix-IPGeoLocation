<meta name="google-site-verification" content="l6lzbHRgJTo4YW5ZB42_qV2MbZoiz_794jZX9MhifZc" />
# Zabbix-IPGeoLocation

IP Geo Location for Zabbix using ipgeolocation.io

This template assigns the following values in the inventory on hosts:
 - ```Site city```
 - ```Site country```
 - ```Location latitude```
 - ```Location longitude```
 - ```Site state / province```
 - ```Site ZIP / postal```

# Setup:
 - Register developer account at ipgeolocation.io
 - Import template to Zabbix
 - Replace value in ```{$APIKEY}``` with your API key
 - Assign template to hosts

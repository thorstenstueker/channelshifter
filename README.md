# channelshifter
System to shift the Chasnnels of used WLAN on RPI; setup Network with Command Line App on Hostapd

While to complex for the users use sudo java -jar channelshifter.jar Networkmode Channel Passphrase NetworkName placeof_hostapd.conf CountryCode

where
Networkmode can be twodotfour for 2.4 GHZ Network and fivedoro for 5 GHZ Network
Channel is the WLAN channel to use for the Network
Passphrase is the Network password
NetworkName is the SSID of the Network
placeof_hostapd.conf is the entire url of the hostapd.conf like /etc/hostapd/hostapd.conf
Country Code is the entire Country Code like country_code=DE

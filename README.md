
# ios-OTA
```
Start 6 Jun 2019
```


## Todo 
- [x] Html page
* a
- [ ] BBB
* b


**Note**
```
http://ios-preload.omumusic.net/ios/install.html
```

**Php**
```
https://stackoverflow.com/questions/13167915/ios-enterprise-ota-distribution-unable-to-download-application

```

**Dropbox**
```
https://stackoverflow.com/questions/26042508/over-the-air-ota-ios-ipa-file-distribution-for-public

Now, if you don't have an SSL enabled server you can upload the Plist file to your Dropbox account while keeping the IPA file on your non-SSL enabled server and use it like this:

1. Get the link to the file. Should be something like this: https://www.dropbox.com/s/a8hpnmq654pmbaw/AppName.plist?dl=0

2. Copy everything starting with /s/..... and remove the ?dl=0 parameter.

3. Create your installation link like this: itms-services://?action=download-manifest&url=https://dl.dropbox.com/s/a8hpnmq654pmbaw/AppName.plist

4. Send the link to your testers to open it on their devices.
```

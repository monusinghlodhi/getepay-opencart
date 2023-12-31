## Getepay Payment Extension for Opencart

This extension utilizes Getepay API and provides seamless integration with OpenCart, allowing payments for Indian merchants via Credit Cards, Debit Cards, Net Banking, Wallets, etc.  without redirecting away from the OpenCart site.

### Installation

Copy all files/folders recursively to opencart installation directory.

Go to Admin Panel, Extensions->Payments and install the Getepay gateway extension.

Click on Edit next to Getepay and do the following:

- Add your Getepay Mid
- Add your Getepay Terminal Id
- Add your Getepay Key
- Add your Getepay IV
- Add your Getepay Url
- Change Order Status to Processing
- Change Plugin status to Enabled

Save the plugin settings

### Installation via Extension Installer

1. Download Getepay Payment gateway extension from Opencart
2. Login to the OpenCart Admin Panel
3. Navigate to Extensions -> Installer and click on button Upload and choose the zip file getepay.ocmod.zip
4. Click install on same page
5. Navigate to Extensions -> Payments and click install on Getepay
6. After installing, click on Edit
7. Enable the extension and set the Getepay Mid, Terminal Id, Key, IV, Url, Order Status and Plugin Status.

### Note:
While installing the Getepay plugin to Opencart 4 make sure to only have these folders/files and no hidden files in your zip folder:  
`admin/`  
`catalog/`   
`install.json`  

### Development

- The `master` branch holds the plugin for OpenCart 4
- The `opencart-3.x` branch holds the plugin for OpenCart 3
- Tags are in either of these three series: `opencart3-x.y.z`

### Support

Visit [https://getepay.in](https://getepay.in) for support requests or email support@getepay.in.
# Magento 2 Hide Price Not Login

This Extension is used for hide price at category and product detail when user not login, included setting at configuration for enable or disable when and setting default wording

## Features:

### Frontend
- hide final price at category
- hide final price at product detail

### Backend
- configuration for enable and disable extension
- setting default wording

## Introduction installation:

### Install Magento 2 Hide Price Not Login
- Download file
- Unzip the file
- Create a folder [root]/app/code/MageHelp/Hideprice
- Copy to folder

### Enable Extension

```
php bin/magento module:enable MageHelp_Hideprice
php bin/magento setup:upgrade
php bin/magento cache:clean
php bin/magento setup:static-content:deploy
```

## Screenshot
![ScreenShot](https://github.com/ralgcorp/HidePrice/blob/master/MageHelp/HidePrice/File/category.png)
![ScreenShot](https://github.com/ralgcorp/HidePrice/blob/master/MageHelp/HidePrice/File/configuration.png)

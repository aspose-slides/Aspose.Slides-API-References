---
title: setRootDirectoryClsid
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/pptoptions/setrootdirectoryclsid/
---

## setRootDirectoryClsid(UUID value)  method

 Represents the object class GUID (CLSID) that is stored in the root directory entry. Can be used for COM
 activation of the document's application.
 The default value is '64818D11-4F9B-11CF-86EA-00AA00B929E8' that corresponds to 'Microsoft Powerpoint.Slide.8'.
 

 
```php
  $pres = new Presentation();
  try {
    $pptOptions = new PptOptions();
    // / set CLSID to 'Microsoft Powerpoint.Show.8'
    $pptOptions->setRootDirectoryClsid(UUID->fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
    $pres->save("pres.ppt", SaveFormat.Ppt, $pptOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---



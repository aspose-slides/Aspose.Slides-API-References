---
title: setWriteProtection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 130
url: /php-java/protectionmanager/setwriteprotection/
---

## setWriteProtection(String password)  method

 Set write protection for this presentation with specified password.
 

 The following sample code shows you how to set a write protection to a presentation.
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $pres->getProtectionManager()->setWriteProtection("123123");
    $pres->save("write-protected-pres.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| password | String | The password. |

### Returns
void


---



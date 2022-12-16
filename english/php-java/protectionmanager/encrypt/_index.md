---
title: encrypt
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/protectionmanager/encrypt/
---

## encrypt(String encryptionPassword)  method

 Encrypts Presentation with specified password.
 

 The following sample code shows you how to encrypt a PowerPoint Presentation.
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $pres->getProtectionManager()->encrypt("123123");
    $pres->save("encrypted-pres.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| encryptionPassword | String | The password. |

### Returns
void


---



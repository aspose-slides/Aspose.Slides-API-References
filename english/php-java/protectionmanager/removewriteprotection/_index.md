---
title: removeWriteProtection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 100
url: /php-java/protectionmanager/removewriteprotection/
---

## removeWriteProtection()  method

 Removes write protection for this presentation.
 

 This sample code shows you how to remove the write protection from a PowerPoint Presentation.
 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $pres->getProtectionManager()->removeWriteProtection();
    $pres->save("write-protection-removed.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
void


---



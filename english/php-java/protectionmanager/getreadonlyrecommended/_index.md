---
title: getReadOnlyRecommended
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/protectionmanager/getreadonlyrecommended/
---

## getReadOnlyRecommended()  method

 Gets or sets read-only recommendation.
 Read/write  boolean.
 

 
```php
  $pres = new Presentation();
  try {
    $pres->getProtectionManager()->setReadOnlyRecommended(true);
    $pres->save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
boolean


---



---
title: setReadOnlyRecommended
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 120
url: /php-java/protectionmanager/setreadonlyrecommended/
---

## setReadOnlyRecommended(boolean value)  method

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
void


---



---
title: getReadOnlyRecommended
type: docs
weight: 50
url: /php-java/protectionmanager/getreadonlyrecommended/
---

# getReadOnlyRecommended() method

 Gets or sets read-only recommendation.
 Read/write  boolean.
 

 
```php
  $pres = new Presentation();
  $pres->getProtectionManager()->setReadOnlyRecommended(true);
  $pres->save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
```

##  Returns
boolean



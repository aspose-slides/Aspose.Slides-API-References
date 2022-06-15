---
title: setReadOnlyRecommended
type: docs
weight: 120
url: /php-java/protectionmanager/setreadonlyrecommended/
---

# setReadOnlyRecommended(boolean) method

 Gets or sets read-only recommendation.
 Read/write  boolean.
 

 
```php
  $pres = new Presentation();
  $pres->getProtectionManager()->setReadOnlyRecommended(true);
  $pres->save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
```

##  Returns
boolean



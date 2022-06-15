---
title: getGlobal
type: docs
weight: 20
url: /php-java/webdocument/getglobal/
---

# getGlobal() method

  Returns global storage of the document.
  Read-only  Storage.
  
Using this ( #getGlobal) property (implementation of  Storage interface) a
  property can be put to use it later in the template:
  
```php
  $options = new WebDocumentOptions();
  $document = new WebDocument($options);
  // put "slideMargin" property to use from templates
  $document->getGlobal()->put("slideMargin", 10);
  // ... set up other options of the document and then save the document
  $document->save();
```

##  Returns
Storage



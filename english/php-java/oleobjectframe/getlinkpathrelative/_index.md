---
title: getLinkPathRelative
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 60
url: /php-java/oleobjectframe/getlinkpathrelative/
---

## getLinkPathRelative()  method

  Returns the relative path to a linked file if present, otherwise returns an empty string.
  Readonly  String.
  
  In the Ppt presentations, some Ole object links may have a relative representation.
  

  
```php
  $presentation = new Presentation("demo.ppt");
  try {
    $oleFrame = $presentation->getSlides()->get_Item(0)->getShapes()->get_Item(0);
    if ($oleFrame != null) {
      echo("The relative path: " + $oleFrame->getLinkPathRelative());
    }
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

### Returns
String


---



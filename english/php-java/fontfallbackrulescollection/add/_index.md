---
title: add
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/fontfallbackrulescollection/add/
---

## add(FontFallBackRule sourceRule)  method

 Add a specified FallBack rule to the end of the collection.
 

 
```php
  $pres = new Presentation();
  try {
    // Getting of empty or preinitialized rules collection from FontsManager
    $rulesList = $pres->getFontsManager()->getFontFallBackRulesCollection();
    // Adding of new rule to collection
    $rulesList->add(new FontFallBackRule(0x400, 0x4ff, "Times New Roman"));
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| sourceRule | Specified rule for adding |


---



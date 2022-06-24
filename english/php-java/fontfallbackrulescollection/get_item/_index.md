---
title: get_Item
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 50
url: /php-java/fontfallbackrulescollection/get_item/
---

## get_Item(int) method

 Gets the rule at the specified index.
 Read-only  IFontFallBackRule.
 

 
```php
  $pres = new Presentation();
  try {
    // Getting of empty or preinitialized rules collection from FontsManager
    $rulesList = $pres->getFontsManager()->getFontFallBackRulesCollection();
    // Adding of several rules to collection
    $rulesList->add(new FontFallBackRule(0x400, 0x4ff, "Times New Roman"));
    $rulesList->add(new FontFallBackRule(0x3040, 0x309f, "MS Mincho"));
    // Retrieving of object of the first rule in collection
    $firstRule = $rulesList->get_Item(0);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
IFontFallBackRule


---



---
title: remove
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 90
url: /php-java/fontfallbackrulescollection/remove/
---

## remove([FontFallBackRule](../../fontfallbackrule) targetRule)  method

 Removes the first occurrence of a specific FallBack rule from the collection.
 

 
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
    // Removing
    $rulesList->remove($firstRule);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| targetRule | [FontFallBackRule](../../fontfallbackrule) | The rule to remove from the collection. |

### Returns
void


---



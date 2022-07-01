---
title: getFontFallBackRulesCollection
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/fontsmanager/getfontfallbackrulescollection/
---

## getFontFallBackRulesCollection()  method

 Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality
 Read/write  IFontFallBackRulesCollection.
 

 
```php
  $pres = new Presentation();
  try {
    // Getting of empty or preinitialized rules collection from FontsManager
    $rulesList = $pres->getFontsManager()->getFontFallBackRulesCollection();
    // adding of rules to collection
    $rulesList->add(new FontFallBackRule(0x400, 0x4ff, "Times New Roman"));
    // or
    // initialization of new instance of rules collection
    $rulesList = new FontFallBackRulesCollection();
    // adding of rules to collection
    $rulesList->add(new FontFallBackRule(0x400, 0x4ff, "Times New Roman"));
    // and replacing of existing collection by the new one in FontsManager
    $pres->getFontsManager()->setFontFallBackRulesCollection($rulesList);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
IFontFallBackRulesCollection


---



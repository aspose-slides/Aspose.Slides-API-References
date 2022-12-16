---
title: getFontsManager
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 170
url: /php-java/presentation/getfontsmanager/
---

## getFontsManager()  method

 Returns fonts manager.
 Read-only  IFontsManager.
 

 The following example shows how to add embedded fonts to PowerPoint Presentation.
 
```php
  // Load presentation
  $pres = new Presentation("Fonts.pptx");
  try {
    // Load source font to be replaced
    $sourceFont = new FontData("Arial");
    $allFonts = $pres->getFontsManager()->getFonts();
    for ($font : $allFonts) {
      $fontAlreadyEmbedded = false;
      $embeddedFonts = $pres->getFontsManager()->getEmbeddedFonts();
      for ($i = 0; $i < $embeddedFonts::$length; $i++) {
        if ($embeddedFonts[$i]->equals($font)) {
          $fontAlreadyEmbedded = true;
          break;
        }
      }
      if (!$fontAlreadyEmbedded) {
        $pres->getFontsManager()->addEmbeddedFont($font, EmbedFontCharacters.All);
      }
    }
    // Save the presentation
    $pres->save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
[FontsManager](../../fontsmanager)


---



---
title: loadExternalFonts
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 40
url: /php-java/fontsloader/loadexternalfonts/
---

## loadExternalFonts(java.lang.String[] directories)  method

 Adds additional folders to seek fonts.
 

 The follow examples shows how to load custom fonts from .TTF
 
```php
  $dataDir = "C:/Fonts";
  // folders to seek fonts
  $folders = new String[]{ $dataDir };
  // Load the custom font directory fonts
  FontsLoader->loadExternalFonts($folders);
  // Do Some work and perform presentation/slides rendering
  $pres = new Presentation("DefaultFonts.pptx");
  try {
    $pres->save("NewFonts_out.pptx", SaveFormat.Pptx);
    // Clear Font Cachce
    FontsLoader->clearCache();
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| directories | java.lang.String[] | Directories to read additional fonts. |

### Returns
void


---



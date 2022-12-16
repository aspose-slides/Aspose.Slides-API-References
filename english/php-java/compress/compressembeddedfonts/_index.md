---
title: compressEmbeddedFonts
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/compress/compressembeddedfonts/
---

## compressEmbeddedFonts([Presentation](../../presentation) pres)  method

 Makes compression of the  Presentation by removing unused characters from embedded fonts.  
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    Compress->compressEmbeddedFonts($pres);
    $pres->save("pres-out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../presentation) | The presentation instance |

### Returns
void


---



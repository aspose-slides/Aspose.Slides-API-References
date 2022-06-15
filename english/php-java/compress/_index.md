---
title: Compress
type: docs
weight: 0
url: /php-java/compress/
---

# Compress class

 Represents a group of methods intended to compress  Presentation.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    Compress->removeUnusedMasterSlides($pres);
    $pres->save("pres-out.pptx", SaveFormat.Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| name | description |
| --- | --- |
| [Compress](/php-java/compress/compress/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [removeUnusedLayoutSlides](/php-java/compress/removeunusedlayoutslides/)(Presentation) | void | Makes compression of the Presentation by removing unused layout slides. |
| [removeUnusedMasterSlides](/php-java/compress/removeunusedmasterslides/)(Presentation) | void | Makes compression of the Presentation by removing unused master slides. |

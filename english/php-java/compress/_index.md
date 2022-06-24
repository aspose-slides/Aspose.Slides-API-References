---
title: Compress
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/compress/
---

## Compress class

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

| Name | Description |
| --- | --- |
| [Compress](compress)() |  |

## Methods

| Name | Description |
| --- | --- |
| [removeUnusedLayoutSlides](removeunusedlayoutslides)(Presentation) | Makes compression of the Presentation by removing unused layout slides. |
| [removeUnusedMasterSlides](removeunusedmasterslides)(Presentation) | Makes compression of the Presentation by removing unused master slides. |

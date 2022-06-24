---
title: ForEach
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/foreach/
---

## ForEach class

 Represents a group of methods intended to iterate over different  Presentation model objects.
 These methods can be useful if you need to iterate and change some Presentation' elements formatting or content,
  e.g. change each portion formatting. 
 

 
```php
  $pres = new Presentation("pres.pptx");
```

## Constructors

| Name | Description |
| --- | --- |
| [ForEach](foreach)() |  |

## Methods

| Name | Description |
| --- | --- |
| [layoutSlide](layoutslide)(Presentation, ForEach.ForEachLayoutSlideCallback) | Iterate each #layoutSlide(Presentation,ForEachLayoutSlideCallback) in the Presentation. |
| [masterSlide](masterslide)(Presentation, ForEach.ForEachMasterSlideCallback) | Iterate each #masterSlide(Presentation,ForEachMasterSlideCallback) in the Presentation. |
| [paragraph](paragraph)(Presentation, ForEach.ForEachParagraphCallback) | Iterate each #paragraph(Presentation,ForEachParagraphCallback) in the Presentation. |
| [portion](portion)(Presentation, ForEach.ForEachPortionCallback) | Iterate each #portion(Presentation,ForEachPortionCallback) in the Presentation. |
| [shape](shape)(Presentation, ForEach.ForEachShapeCallback) | Iterate each Shape in the Presentation. |
| [shape](shape)(BaseSlide, ForEach.ForEachShapeCallback) | Iterate each Shape in the BaseSlide. |
| [slide](slide)(Presentation, ForEach.ForEachSlideCallback) | Iterate each #slide(Presentation,ForEachSlideCallback) in the Presentation. |

---
title: ForEach_
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/foreach_/
---

## ForEach_ class

 Represents a group of methods intended to iterate over different  Presentation model objects.
 These methods can be useful if you need to iterate and change some Presentation' elements formatting or content,
  e.g. change each portion formatting. 
 

 
```php
  $pres = new Presentation("pres.pptx");
```

## Constructors

| Name | Description |
| --- | --- |
| [ForEach_](foreach_)() |  |

## Methods

| Name | Description |
| --- | --- |
| [layoutSlide](layoutslide)([Presentation](../presentation), [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback)) | Iterate each #layoutSlide(Presentation,ForEachLayoutSlideCallback) in the Presentation. |
| [masterSlide](masterslide)([Presentation](../presentation), [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback)) | Iterate each #masterSlide(Presentation,ForEachMasterSlideCallback) in the Presentation. |
| [paragraph](paragraph)([Presentation](../presentation), [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | Iterate each #paragraph(Presentation,ForEachParagraphCallback) in the Presentation. |
| [portion](portion)([Presentation](../presentation), [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | Iterate each #portion(Presentation,ForEachPortionCallback) in the Presentation. |
| [shape](shape)([Presentation](../presentation), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Iterate each Shape in the Presentation. |
| [shape](shape)([BaseSlide](../baseslide), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Iterate each Shape in the BaseSlide. |
| [slide](slide)([Presentation](../presentation), [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback)) | Iterate each #slide(Presentation,ForEachSlideCallback) in the Presentation. |

---
title: ForEach
type: docs
weight: 0
url: /php-java/foreach/
---

# ForEach class

 Represents a group of methods intended to iterate over different  Presentation model objects.
 These methods can be useful if you need to iterate and change some Presentation' elements formatting or content,
  e.g. change each portion formatting. 
 

 
```php
  $pres = new Presentation("pres.pptx");
```

## Constructors

| name | description |
| --- | --- |
| [ForEach](/slides/php-java/foreach/foreach/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [layoutSlide](/slides/php-java/foreach/layoutslide/)(Presentation, ForEach.ForEachLayoutSlideCallback) | void | Iterate each #layoutSlide(Presentation,ForEachLayoutSlideCallback) in the Presentation. |
| [masterSlide](/slides/php-java/foreach/masterslide/)(Presentation, ForEach.ForEachMasterSlideCallback) | void | Iterate each #masterSlide(Presentation,ForEachMasterSlideCallback) in the Presentation. |
| [paragraph](/slides/php-java/foreach/paragraph/)(Presentation, ForEach.ForEachParagraphCallback) | void | Iterate each #paragraph(Presentation,ForEachParagraphCallback) in the Presentation. |
| [portion](/slides/php-java/foreach/portion/)(Presentation, ForEach.ForEachPortionCallback) | void | Iterate each #portion(Presentation,ForEachPortionCallback) in the Presentation. |
| [shape](/slides/php-java/foreach/shape/)(Presentation, ForEach.ForEachShapeCallback) | void | Iterate each Shape in the Presentation. |
| [shape](/slides/php-java/foreach/shape/)(BaseSlide, ForEach.ForEachShapeCallback) | void | Iterate each Shape in the BaseSlide. |
| [slide](/slides/php-java/foreach/slide/)(Presentation, ForEach.ForEachSlideCallback) | void | Iterate each #slide(Presentation,ForEachSlideCallback) in the Presentation. |

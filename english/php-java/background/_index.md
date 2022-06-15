---
title: Background
type: docs
weight: 0
url: /php-java/background/
---

# Background class

 Represents background of a slide.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getEffectFormat](/slides/php-java/background/geteffectformat/)() | IEffectFormat | Returns a EffectFormat for BackgroundType.OwnBackground fill. Read-only IEffectFormat. |
| [getEffective](/slides/php-java/background/geteffective/)() | IBackgroundEffectiveData | Gets effective background data with the inheritance applied. |
| [getFillFormat](/slides/php-java/background/getfillformat/)() | IFillFormat | Returns a FillFormat for BackgroundType.OwnBackground fill. Read-only IFillFormat. |
| [getPresentation](/slides/php-java/background/getpresentation/)() | Presentation | Returns the parent presentation of a slide. Read-only IPresentation. |
| [getSlide](/slides/php-java/background/getslide/)() | BaseSlide | Returns the parent slide of a shape. Read-only IBaseSlide. |
| [getStyleColor](/slides/php-java/background/getstylecolor/)() | IColorFormat | Return a ColorFormat for a BackgroundType.Themed fill. Read-only IColorFormat. |
| [getStyleIndex](/slides/php-java/background/getstyleindex/)() | int | Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. Read/write int. |
| [getType](/slides/php-java/background/gettype/)() | byte | Returns a type of background fill. Read/write BackgroundType. |
| [setStyleIndex](/slides/php-java/background/setstyleindex/)(int) | void | Returns an index of BackgroundType.Themed fill in background theme collection. 0 means no fill. 1..999 - index. Read/write int. |
| [setType](/slides/php-java/background/settype/)(byte) | void | Returns a type of background fill. Read/write BackgroundType. |

---
title: SlideImageFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Bestämmer formatet i vilket bildspelsbilden sparas för presentation till HTML-export.
type: docs
url: /sv/com.aspose.slides/slideimageformat/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Bestämmer formatet som bilden på bildspel sparas i för presentation till HTML-export.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slides should converted to a SVG format. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slides should be converted to a raster image. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Bildspel bör konverteras till SVG-format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Alternativ för SVG-export. |

**Returnerar:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Objektet [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Bildspel bör konverteras till en rasterbild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scale | float | Faktorn som bilden skalas med för den utgående bilden. |
| imageFormat | int | Formatet på den resulterande bilden (t.ex. PNG, JPEG). |

**Returnerar:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
---
title: SlideImageFormat
second_title: Aspose.Slides för Java API-referens
description: Bestämmer formatet som bilden på bilden sparas i för presentation vid HTML-export.
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

Bestämmer formatet som bilden på bilden sparas i för presentation vid HTML-export.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Bilderna bör konverteras till ett SVG-format. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Bilderna bör konverteras till en rasterbild. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Bilderna bör konverteras till ett SVG-format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Alternativ för SVG-export. |

**Returnerar:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - [SlideImageFormat](../../com.aspose.slides/slideimageformat)-objektet.
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Bilderna bör konverteras till en rasterbild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scale | float | Faktorn som används för att skala utdata-bilden. |
| imageFormat | int | Formatet på den resulterande bilden (t.ex. PNG, JPEG). |

**Returnerar:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
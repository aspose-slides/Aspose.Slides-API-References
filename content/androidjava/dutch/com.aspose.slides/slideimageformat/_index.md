---
title: SlideImageFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Bepaalt het formaat waarin de dia-afbeelding wordt opgeslagen voor weergave bij HTML-export.
type: docs
url: /nl/com.aspose.slides/slideimageformat/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Bepaalt het formaat waarin de dia-afbeelding wordt opgeslagen voor weergave bij HTML-export.
## Constructors

| Constructor | Description |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Methods

| Method | Description |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Dia's moeten worden geconverteerd naar SVG-formaat. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Dia's moeten worden geconverteerd naar een rasterafbeelding. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Dia's moeten worden geconverteerd naar SVG-formaat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Opties voor SVG-export. |

**Retour:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Het [SlideImageFormat](../../com.aspose.slides/slideimageformat) object.
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Dia's moeten worden geconverteerd naar een rasterafbeelding.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scale | float | De factor waarmee de uitvoerafbeelding moet worden geschaald. |
| imageFormat | int | Het formaat van de resulterende afbeelding (bijv. PNG, JPEG). |

**Retour:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
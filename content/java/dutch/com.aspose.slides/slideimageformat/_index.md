---
title: SlideImageFormat
second_title: Aspose.Slides voor Java API Referentie
description: Bepaalt het formaat waarin de dia-afbeelding wordt opgeslagen voor presentatie bij HTML-export.
type: docs
url: /nl/com.aspose.slides/slideimageformat/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Bepaalt het formaat waarin de diaafbeelding wordt opgeslagen voor presentatie bij HTML-export.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Dia's moeten worden geconverteerd naar een SVG-formaat. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Dia's moeten worden geconverteerd naar een rasterafbeelding. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Dia's moeten worden geconverteerd naar een SVG-formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scale | float | De factor waarmee de uitvoerafbeelding moet worden geschaald. |
| imageFormat | int | Het formaat van de resulterende afbeelding (bijv. PNG, JPEG). |

**Retour:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
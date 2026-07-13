---
title: SlideImageFormat
second_title: Aspose.Slides pro Android přes rozhraní Java API
description: Určuje formát, ve kterém bude obrázek snímku uložen pro export prezentace do HTML.
type: docs
url: /cs/com.aspose.slides/slideimageformat/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Určuje formát, ve kterém bude obrázek snímku uložen pro export prezentace do HTML.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Snímky by měly být převedeny do formátu SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Snímky by měly být převedeny na rastrový obrázek. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Snímky by měly být převedeny do formátu SVG.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Možnosti pro export SVG. |

**Vrací:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Objekt [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Snímky by měly být převedeny na rastrový obrázek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| scale | float | Faktor, o který se má výstupní obrázek zvětšit. |
| imageFormat | int | Formát výsledného obrázku (např. PNG, JPEG). |

**Vrací:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
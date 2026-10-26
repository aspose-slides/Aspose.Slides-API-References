---
title: SlideImageFormat
second_title: Aspose.Slides dla Java – Referencja API
description: Określa format, w którym obraz slajdu zostanie zapisany przy eksporcie prezentacji do HTML.
type: docs
url: /pl/com.aspose.slides/slideimageformat/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Określa format, w którym obraz slajdu zostanie zapisany dla eksportu prezentacji do HTML.

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## Metody

| Metoda | Opis |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slajdy powinny być konwertowane do formatu SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slajdy powinny być konwertowane do obrazu rastrowego. |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Slajdy powinny być konwertowane do formatu SVG.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Opcje eksportu SVG. |

**Zwraca:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Obiekt [SlideImageFormat](../../com.aspose.slides/slideimageformat).

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Slajdy powinny być konwertowane do obrazu rastrowego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| scale | float | Czynnik, o którym skalowany jest obraz wyjściowy. |
| imageFormat | int | Format powstałego obrazu (np. PNG, JPEG). |

**Zwraca:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
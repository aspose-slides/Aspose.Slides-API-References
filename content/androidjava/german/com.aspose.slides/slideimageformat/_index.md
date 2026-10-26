---
title: SlideImageFormat
second_title: Aspose.Slides für Android über die Java API Referenz
description: Bestimmt das Format, in dem das Folienbild für die Präsentation beim HTML-Export gespeichert wird.
type: docs
url: /de/com.aspose.slides/slideimageformat/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Bestimmt das Format, in dem Folienbilder für die Präsentation im HTML-Export gespeichert werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Folien sollten in ein SVG-Format konvertiert werden. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Folien sollten in ein Rasterbild konvertiert werden. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Folien sollten in ein SVG-Format konvertiert werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Optionen für den SVG-Export. |

**Rückgabewert:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Das [SlideImageFormat](../../com.aspose.slides/slideimageformat)-Objekt.
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Folien sollten in ein Rasterbild konvertiert werden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scale | float | Der Faktor, um den das Ausgabebild skaliert wird. |
| imageFormat | int | Das Format des resultierenden Bildes (z. B. PNG, JPEG). |

**Rückgabewert:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
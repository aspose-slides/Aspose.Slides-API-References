---
title: SlideImageFormat
second_title: Aspose.Slides Androidra a Java API hivatkozásával
description: Meghatározza a formátumot, amelyben a diakép el lesz mentve a HTML exporthoz.
type: docs
url: /hu/com.aspose.slides/slideimageformat/
---
**Öröklés:**  
java.lang.Object

**Minden megvalósított interfész:**  
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)  
```
public class SlideImageFormat implements ISlideImageFormat
```

Meghatározza a formátumot, amelyben a diakép el lesz mentve a HTML exporthoz.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | A diákok SVG formátumba lesznek konvertálva. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | A diákok raszteres képpé lesznek konvertálva. |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

A diákok SVG formátumba lesznek konvertálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Az SVG exportáláshoz szükséges beállítások. |

**Visszatérési érték:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - A [SlideImageFormat](../../com.aspose.slides/slideimageformat) objektum.

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

A diákok raszteres képpé lesznek konvertálva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scale | float | A kimeneti kép méretezésének tényezője. |
| imageFormat | int | A létrehozott kép formátuma (pl. PNG, JPEG). |

**Visszatérési érték:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -
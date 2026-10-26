---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: HTML fájl generálásának vezérlése.
type: docs
url: /hu/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

HTML fájl generálásának vezérlése.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML dokumentum fejlécének írására hívják. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | HTML dokumentum láblécének írására hívják. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML dia fejlécének írására hívják. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | HTML dia láblécének írására hívják. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Az alakzat renderelése előtt hívják. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Az alakzat renderelése előtt hívják. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTML dokumentum fejlécének írására hívják. Az átalakítás minden prezentációjára egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Jelenleg renderelt prezentáció. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTML dokumentum láblécének írására hívják. Az átalakítás minden prezentációjára egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Jelenleg renderelt prezentáció. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTML dia fejlécének írására hívják. Minden diára egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| slide | [ISlide](../../com.aspose.slides/islide) | Jelenleg renderelt dia. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTML dia láblécének írására hívják. Minden diára egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| slide | [ISlide](../../com.aspose.slides/islide) | Jelenleg renderelt dia. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Az alakzat renderelése előtt hívják. Minden alakzatra egyszer hívják. Ha ez a függvény bármit ír a generatorba, a jelenlegi dia kép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép lesz indítva az előző tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| shape | [IShape](../../com.aspose.slides/ishape) | Renderelésre váró alakzat. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Az alakzat renderelése előtt hívják. Minden alakzatra egyszer hívják. Ha ez a függvény bármit ír a generatorba, a jelenlegi dia kép generálása befejeződik, a hozzáadott HTML töredék beillesztésre kerül, és egy új kép lesz indítva az előző tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| shape | [IShape](../../com.aspose.slides/ishape) | Utoljára renderelt alakzat. |
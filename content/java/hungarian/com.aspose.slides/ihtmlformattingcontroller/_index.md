---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: HTML-fájl generálását vezérli.
type: docs
url: /hu/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

HTML-fájl generálását vezérli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | A HTML-dokumentum fejléce írásához hívják. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | A HTML-dokumentum lábléce írásához hívják. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | A HTML-diavetítő fejléce írásához hívják. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | A HTML-diavetítő lábléce írásához hívják. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | A forma megjelenítése előtt hívják. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | A forma megjelenítése előtt hívják. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


A HTML-dokumentum fejléce írásához hívják. Egy alkalommal hívják egy prezentáció átalakítása során.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | A jelenleg renderelt prezentáció. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


A HTML-dokumentum lábléce írásához hívják. Egy alkalommal hívják egy prezentáció átalakítása során.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | A jelenleg renderelt prezentáció. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


A HTML-diavetítő fejléce írásához hívják. Minden diának egyszer meghívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| slide | [ISlide](../../com.aspose.slides/islide) | A jelenleg renderelt dia. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


A HTML-diavetítő lábléce írásához hívják. Minden diának egyszer meghívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| slide | [ISlide](../../com.aspose.slides/islide) | A jelenleg renderelt dia. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


A forma megjelenítése előtt hívják. Minden forma esetén egyszer hívják. Ha ez a függvény bármit ír a generator-ba, a jelenlegi dia kép generálása befejeződik, a hozzáadott HTML-töredék beillesztésre kerül, és egy új kép indul a korábbi tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| shape | [IShape](../../com.aspose.slides/ishape) | A renderelésre váró forma. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


A forma megjelenítése előtt hívják. Minden forma esetén egyszer hívják. Ha ez a függvény bármit ír a generator-ba, a jelenlegi dia kép generálása befejeződik, a hozzáadott HTML-töredék beillesztésre kerül, és egy új kép indul a korábbi tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Kimeneti objektum. |
| shape | [IShape](../../com.aspose.slides/ishape) | Az utoljára renderelt forma. |
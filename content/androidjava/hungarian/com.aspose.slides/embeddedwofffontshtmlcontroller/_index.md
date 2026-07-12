---
title: EmbeddedWoffFontsHtmlController
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: A formázási vezérlő osztály a betűtípusok WOFF formátumban való beágyazásához
type: docs
url: /hu/com.aspose.slides/embeddedwofffontshtmlcontroller/
---
**Öröklődés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IEmbeddedWoffFontsHtmlController](../../com.aspose.slides/iembeddedwofffontshtmlcontroller)
```
public class EmbeddedWoffFontsHtmlController implements IEmbeddedWoffFontsHtmlController
```

A WOFF formátumban betűtípusok beágyazásához használandó formázási vezérlő osztály
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [EmbeddedWoffFontsHtmlController()](#EmbeddedWoffFontsHtmlController--) | Új példányt hoz létre. |
| [EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | Új példányt hoz létre. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### EmbeddedWoffFontsHtmlController() {#EmbeddedWoffFontsHtmlController--}
```
public EmbeddedWoffFontsHtmlController()
```


Új példányt hoz létre.

### EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)
```


Új példányt hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | HTML formázási vezérlő. |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


HTML dokumentumfejléc írásához hívják. Prezentációkonverziónként egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


HTML dokumentum lábléc írásához hívják. Prezentációkonverziónként egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


HTML diavetítés fejléce írásához hívják. Minden diára egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


HTML diavetítés láblécéhez hívják. Minden diára egyszer hívják.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Az alakzat renderelése előtt hívják. Minden alakzatra egyszer hívják. Ha ez a függvény bármit ír a generator-ba, az aktuális dia kép generálása befejeződik, a hozzáadott HTML töredék beszúródik, és egy új kép indul az előző tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Az alakzat renderelése előtt hívják. Minden alakzatra egyszer hívják. Ha ez a függvény bármit ír a generator-ba, az aktuális dia kép generálása befejeződik, a hozzáadott HTML töredék beszúródik, és egy új kép indul az előző tetején.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |
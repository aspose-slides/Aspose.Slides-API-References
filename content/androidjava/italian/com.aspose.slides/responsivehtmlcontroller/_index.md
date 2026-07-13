---
title: ResponsiveHtmlController
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Controller HTML responsivo
type: docs
url: /it/com.aspose.slides/responsivehtmlcontroller/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IResponsiveHtmlController](../../com.aspose.slides/iresponsivehtmlcontroller)
```
public class ResponsiveHtmlController implements IResponsiveHtmlController
```

Responsive HTML Controller
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ResponsiveHtmlController()](#ResponsiveHtmlController--) | Crea una nuova istanza |
| [ResponsiveHtmlController(IHtmlFormattingController controller)](#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-) | Crea una nuova istanza |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### ResponsiveHtmlController() {#ResponsiveHtmlController--}
```
public ResponsiveHtmlController()
```

Crea una nuova istanza

### ResponsiveHtmlController(IHtmlFormattingController controller) {#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public ResponsiveHtmlController(IHtmlFormattingController controller)
```

Crea una nuova istanza

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | controller di formattazione HTML |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Chiamato per scrivere l'intestazione del documento html. Chiamato una volta per conversione della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Chiamato per scrivere il piè di pagina del documento html. Chiamato una volta per conversione della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Chiamato per scrivere l'intestazione della diapositiva html. Chiamato una volta per ciascuna diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Chiamato per scrivere il piè di pagina della diapositiva html. Chiamato una volta per ciascuna diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa sul generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto verrà inserito e una nuova immagine verrà avviata sopra la precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa sul generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto verrà inserito e una nuova immagine verrà avviata sopra la precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |
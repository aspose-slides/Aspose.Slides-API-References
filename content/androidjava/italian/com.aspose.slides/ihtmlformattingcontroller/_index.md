---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controlla la generazione di un file HTML.
type: docs
url: /it/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Controlla la generazione di un file HTML.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Chiamato per scrivere l'intestazione del documento HTML. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Chiamato per scrivere il piè di pagina del documento HTML. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Chiamato per scrivere l'intestazione della diapositiva HTML. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Chiamato per scrivere il piè di pagina della diapositiva HTML. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Chiamato prima del rendering della forma. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Chiamato prima del rendering della forma. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Chiamato per scrivere l'intestazione del documento HTML. Viene chiamato una volta per conversione della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione attualmente in fase di rendering. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Chiamato per scrivere il piè di pagina del documento HTML. Viene chiamato una volta per conversione della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione attualmente in fase di rendering. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Chiamato per scrivere l'intestazione della diapositiva HTML. Viene chiamato una volta per ciascuna diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva attualmente in fase di rendering. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Chiamato per scrivere il piè di pagina della diapositiva HTML. Viene chiamato una volta per ciascuna diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva attualmente in fase di rendering. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Chiamato prima del rendering della forma. Viene chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa nel generatore, la generazione dell’immagine della diapositiva corrente sarà completata, il frammento HTML aggiunto verrà inserito e una nuova immagine sarà avviata sopra la precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma che sta per essere renderizzata. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Chiamato prima del rendering della forma. Viene chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa nel generatore, la generazione dell’immagine della diapositiva corrente sarà completata, il frammento HTML aggiunto verrà inserito e una nuova immagine sarà avviata sopra la precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma che è stata renderizzata per ultima. |
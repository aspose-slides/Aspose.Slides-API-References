---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: La classe del controller di formattazione da utilizzare per incorporare tutti i font della presentazione in formato WOFF.
type: docs
url: /it/com.aspose.slides/embedallfontshtmlcontroller/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

La classe del controller di formattazione da utilizzare per incorporare tutti i font della presentazione in formato WOFF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Crea una nuova istanza |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Crea una nuova istanza |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Chiamato per scrivere l'intestazione del documento html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Chiamato per scrivere il piè di pagina del documento html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Chiamato per scrivere l'intestazione della diapositiva html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Chiamato per scrivere il piè di pagina della diapositiva html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Chiamato prima del rendering della forma. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Chiamato prima del rendering della forma. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Scrivi tutti i font contenuti in [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Scrive i dati come base64 nel documento HTML stesso |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

Crea una nuova istanza

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

Crea una nuova istanza

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Font da escludere dall'incorporamento |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Chiamato per scrivere l'intestazione del documento html. Chiamato una volta per ogni conversione della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione attualmente in fase di rendering. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Chiamato per scrivere il piè di pagina del documento html. Chiamato una volta per ogni conversione della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione attualmente in fase di rendering. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Chiamato per scrivere l'intestazione della diapositiva html. Chiamato una volta per ciascuna diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva attualmente in fase di rendering. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Chiamato per scrivere il piè di pagina della diapositiva html. Chiamato una volta per ciascuna diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva attualmente in fase di rendering. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Chiamato prima del rendering della forma. Chiamato una volta per ogni forma. Se questa funzione scrive qualcosa sul generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto sarà inserito e una nuova immagine verrà avviata sopra la precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma che sta per essere renderizzata. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Chiamato prima del rendering della forma. Chiamato una volta per ogni forma. Se questa funzione scrive qualcosa sul generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto sarà inserito e una nuova immagine verrà avviata sopra la precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma renderizzata per ultima. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Scrivi tutti i font contenuti in [Presentation](../../com.aspose.slides/presentation).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione attualmente in fase di rendering. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Scrive i dati come base64 nel documento HTML stesso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Generatore HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Font da serializzare |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Font sostituito (se è avvenuta la sostituzione del font), null altrimenti |
| fontStyle | java.lang.String | Stile del font |
| fontWeight | java.lang.String | Peso del font |
| fontData | byte[] | Dati del font |
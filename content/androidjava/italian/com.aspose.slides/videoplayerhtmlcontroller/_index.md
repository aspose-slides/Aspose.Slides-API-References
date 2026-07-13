---
title: VideoPlayerHtmlController
second_title: Riferimento API Java di Aspose.Slides per Android
description: Questa classe consente l'esportazione di file video e audio in un HTML
type: docs
url: /it/com.aspose.slides/videoplayerhtmlcontroller/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

Questa classe consente l'esportazione di file video e audio in un HTML

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | Crea una nuova istanza del controller |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |

### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```

Crea una nuova istanza del controller

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Il percorso in cui verranno generati i file video e audio |
| fileName | java.lang.String | Il nome del file HTML |
| baseUri | java.lang.String | L'URI di base che verrà utilizzato per generare i collegamenti |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Chiamato per scrivere l'intestazione del documento HTML. Chiamato una sola volta per ogni conversione di presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Chiamato per scrivere il piè di pagina del documento HTML. Chiamato una sola volta per ogni conversione di presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Chiamato per scrivere l'intestazione della diapositiva HTML. Chiamato una sola volta per ciascuna diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Chiamato per scrivere il piè di pagina della diapositiva HTML. Chiamato una sola volta per ciascuna diapositiva.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Chiamato prima del rendering della forma. Chiamato una sola volta per ciascuna forma. Se questa funzione scrive qualcosa nel generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento HTML aggiunto verrà inserito e una nuova immagine verrà avviata sopra la precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Chiamato prima del rendering della forma. Chiamato una sola volta per ciascuna forma. Se questa funzione scrive qualcosa nel generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento HTML aggiunto verrà inserito e una nuova immagine verrà avviata sopra la precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```

Questa funzione è chiamata prima del rendering della forma in SVG per consentire all'utente di controllare l'SVG risultante.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```

Determina dove l'oggetto dovrebbe essere archiviato. Questo metodo è chiamato una volta per ogni ID oggetto. Non è garantito che non esistano due oggetti con gli stessi dati, semanticName e contentType ma con ID diversi.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**Restituisce:**
int

### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```

Restituisce un URL a un oggetto esterno. Questo metodo è sempre chiamato se \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ha restituito [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) e può essere chiamato se \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) ha restituito [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) ma l'incorporamento è impossibile. Può essere chiamato più volte per lo stesso ID oggetto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**Restituisce:**
java.lang.String

### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```

Salva l'oggetto esterno.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |

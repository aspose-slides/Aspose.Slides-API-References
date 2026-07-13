---
title: Output
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di elementi di output per IWebDocument.
type: docs
url: /it/com.aspose.slides/output/
---
**Ereditarietà:**
java.lang.Object
```
public final class Output
```

Rappresenta una raccolta di elementi di output per IWebDocument.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Aggiunge un elemento di output per l'oggetto di contesto. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Aggiunge un elemento di output per l'immagine. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Aggiunge un elemento di output per l'immagine. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Aggiunge un elemento di output per il video. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Crea e aggiunge un elemento di file di output per il font specificato. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Aggiunge un elemento di output per il contenuto di testo. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Associa la risorsa al file di output. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Restituisce il percorso per una risorsa data. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Aggiunge un elemento di output per l'oggetto di contesto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Percorso di output. |
| templateKey | java.lang.String | La chiave del modello usato per la trasformazione dell'oggetto di contesto prima dell'output. |
| contextObject | TContextObject | Oggetto di contesto. |

**Restituisce:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) oggetto per l'oggetto di contesto.
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

Aggiunge un elemento di output per l'immagine.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Percorso di output. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Immagine da output. |

**Restituisce:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) oggetto per l'immagine.
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

Aggiunge un elemento di output per l'immagine.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Percorso di output. |
| image | [IImage](../../com.aspose.slides/iimage) | Immagine da output. |

**Restituisce:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) oggetto per l'immagine.
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

Aggiunge un elemento di output per il video.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Percorso di output. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video da output. |

**Restituisce:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) oggetto per il video.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Crea e aggiunge un elemento di file di output per il font specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Il percorso del file in cui il font di output sarà salvato. |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | I dati del font da scrivere nell'output. |
| fontStyle | int | Lo stile del font (ad es., Regular, Bold, Italic). |

**Restituisce:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - Un'istanza [IOutputFile](../../com.aspose.slides/ioutputfile) per il font generato.
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

Aggiunge un elemento di output per il contenuto di testo.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Percorso di output. |
| textContent | java.lang.String | Contenuto da output. |

**Restituisce:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) oggetto per il contenuto di testo.
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

Associa la risorsa al file di output.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | File di output. |
| obj | java.lang.Object | Oggetto risorsa. |

### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

Restituisce il percorso per una risorsa data.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Oggetto risorsa. |

**Restituisce:**
java.lang.String - Percorso della risorsa.
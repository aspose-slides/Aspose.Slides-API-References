---
title: Output
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di elementi di output per IWebDocument.
type: docs
url: /it/com.aspose.slides/output/
---
**Eredità:**
java.lang.Object
```
public final class Output
```

Rappresenta una raccolta di elementi di output per IWebDocument.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adds an output element for the context object. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adds an output element for the image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adds an output element for the image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adds an output element for the video. |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | Adds an output element for the audio. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creates and adds an output file element for the specified font. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adds an output element for the text content. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binds resource to output file. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returns the path for a given resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

Aggiunge un elemento di output per l'oggetto di contesto.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| templateKey | java.lang.String | The key of the template used for context object transformation before output. |
| contextObject | TContextObject | Context object. |

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
| path | java.lang.String | Output path. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Immagine da esportare. |

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
| path | java.lang.String | Output path. |
| image | [IImage](../../com.aspose.slides/iimage) | Immagine da esportare. |

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
| path | java.lang.String | Output path. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video da esportare. |

**Restituisce:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) oggetto per il video.
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

Aggiunge un elemento di output per l'audio.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Output path. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio da esportare. |

**Restituisce:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) oggetto per l'audio.
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

Crea e aggiunge un elemento di file di output per il font specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | java.lang.String | Il percorso del file in cui verrà salvato l'output del font. |
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
| path | java.lang.String | Output path. |
| textContent | java.lang.String | Contenuto da esportare. |

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

Restituisce il percorso per una risorsa fornita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Oggetto risorsa. |

**Restituisce:**
java.lang.String - Percorso della risorsa.
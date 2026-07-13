---
title: Video
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un'immagine incorporata in una presentazione.
type: docs
url: /it/com.aspose.slides/video/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Rappresenta un'immagine incorporata in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContentType()](#getContentType--) | Restituisce un tipo MIME di un video, codificato in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Restituisce una copia dei dati di un audio. |
| [getStream()](#getStream--) | Restituisce lo Stream per la lettura. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Restituisce un tipo MIME di un video, codificato in (\#getBinaryData.getBinaryData). Stringa di sola lettura.

**Restituisce:**
java.lang.String

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Restituisce una copia dei dati di un audio. In caso di una grande quantità di dati considerare l'uso del metodo \#getStream.getStream per evitare il caricamento non necessario dei dati del video in memoria o addirittura un OutOfMemoryException. byte[] di sola lettura.

**Restituisce:**
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

Restituisce lo Stream per la lettura. Usa 'using' o chiudi lo stream dopo l'uso.

**Restituisce:**
java.io.InputStream - Stream per la lettura.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. IDOMObject di sola lettura.

**Restituisce:**
com.aspose.slides.IDOMObject
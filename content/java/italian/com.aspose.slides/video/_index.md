---
title: Video
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un'immagine incorporata in una presentazione.
type: docs
url: /it/com.aspose.slides/video/
---
**Eredità:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

Rappresenta un'immagine incorporata in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContentType()](#getContentType--) | Restituisce un tipo MIME di un video, codificato in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Restituisce la copia dei dati di un audio. |
| [getStream()](#getStream--) | Restituisce lo Stream per la lettura. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Restituisce un tipo MIME di un video, codificato in (\#getBinaryData.getBinaryData). Solo lettura String.

**Restituisce:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Restituisce la copia dei dati di un audio. In caso di grandi quantità di dati, considerare l'uso del metodo \#getStream.getStream per evitare il caricamento non necessario dei dati del video in memoria o persino un OutOfMemoryException. Solo lettura byte[].

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


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
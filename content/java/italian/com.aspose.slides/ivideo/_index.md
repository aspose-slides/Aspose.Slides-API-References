---
title: IVideo
second_title: Aspose.Slides per Java API Reference
description: Rappresenta un video incorporato in una presentazione.
type: docs
url: /it/com.aspose.slides/ivideo/
---```
public interface IVideo
```

Rappresenta un video incorporato in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContentType()](#getContentType--) | Restituisce un tipo MIME di un video, codificato in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Restituisce la copia dei dati di un audio. |
| [getStream()](#getStream--) | Restituisce lo Stream per la lettura. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Restituisce un tipo MIME di un video, codificato in (\#getBinaryData.getBinaryData). String di sola lettura.

**Returns:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Restituisce la copia dei dati di un audio. In caso di grande quantità di dati, considerare l'uso del metodo \#getStream.getStream per evitare il caricamento non necessario dei dati del video in memoria o persino un OutOfMemoryException. byte[] di sola lettura.

**Returns:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Restituisce lo Stream per la lettura. Utilizzare 'using' o chiudere lo stream dopo l'uso.

**Returns:**
java.io.InputStream - Stream per la lettura.
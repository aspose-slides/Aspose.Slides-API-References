---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /it/com.aspose.slides/iaudio/
---```
public interface IAudio
```

Rappresenta un file audio incorporato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContentType()](#getContentType--) | Restituisce un tipo MIME di un audio, codificato in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Restituisce la copia dei dati di un audio. |
| [getStream()](#getStream--) | Restituisce lo Stream per la lettura. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Restituisce un tipo MIME di un audio, codificato in (\#getBinaryData.getBinaryData). Solo lettura String.

**Restituisce:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Restituisce la copia dei dati di un audio. In caso di grandi quantità di dati considerare l'uso del metodo \#getStream.getStream per evitare il caricamento non necessario dei dati audio in memoria o anche un OutOfMemoryException. Solo lettura byte[].

**Restituisce:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


Restituisce lo Stream per la lettura. Usare 'using' o chiudere lo stream dopo l'uso.

**Restituisce:**
java.io.InputStream - Stream per la lettura.
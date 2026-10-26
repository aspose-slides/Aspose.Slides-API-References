---
title: IAudio
second_title: Aspose.Slides for Android via Java API Reference
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
| [getBinaryData()](#getBinaryData--) | Restituisce una copia dei dati di un audio. |
| [getStream()](#getStream--) | Restituisce lo stream Stream per la lettura. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Restituisce un tipo MIME di un audio, codificato in (\#getBinaryData.getBinaryData). Stringa di sola lettura.

**Restituisce:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Restituisce una copia dei dati di un audio. In caso di grandi quantità di dati, considerare l'utilizzo del metodo \#getStream.getStream per evitare il caricamento non necessario dei dati audio nella memoria o anche un OutOfMemoryException. byte[] di sola lettura.

**Restituisce:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

Restituisce lo stream Stream per la lettura. Utilizzare 'using' o chiudere lo stream dopo l'uso.

**Restituisce:**  
java.io.InputStream - Stream per la lettura.
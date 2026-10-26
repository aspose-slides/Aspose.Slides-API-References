---
title: Audio
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un file audio incorporato.
type: docs
url: /it/com.aspose.slides/audio/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

Rappresenta un file audio incorporato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContentType()](#getContentType--) | Restituisce un tipo MIME di un audio, codificato in (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | Restituisce un tipo MIME di un audio, codificato in (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | Restituisce una copia dei dati di un audio. |
| [getStream()](#getStream--) | Restituisce lo stream Stream per la lettura. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Restituisce un tipo MIME di un audio, codificato in (\#getBinaryData.getBinaryData). String in sola lettura.

**Restituisce:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Restituisce un tipo MIME di un audio, codificato in (\#getBinaryData.getBinaryData). String in sola lettura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Restituisce una copia dei dati di un audio. In caso di una grande quantità di dati considerare l'uso del metodo \#getStream.getStream per evitare il caricamento non necessario dei dati audio in memoria o anche un OutOfMemoryException. byte[] in sola lettura.

**Restituisce:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

Restituisce lo stream Stream per la lettura. Usare 'using' o chiudere lo stream dopo l'uso.

**Restituisce:**
java.io.InputStream - Stream per la lettura.
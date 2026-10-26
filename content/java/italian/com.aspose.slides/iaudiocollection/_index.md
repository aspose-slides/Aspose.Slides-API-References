---
title: IAudioCollection
second_title: Aspose.Slides per Java Riferimento API
description: Rappresenta una raccolta di file audio incorporati.
type: docs
url: /it/com.aspose.slides/iaudiocollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Rappresenta una collezione di file audio incorporati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Aggiunge una copia di un file audio da un'altra presentazione. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Crea e aggiunge un audio a una presentazione da stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Crea e aggiunge un audio a una presentazione da stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Crea e aggiunge un audio a una presentazione da un array di byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

Restituisce l'elemento all'indice specificato. Sola lettura [IAudio](../../com.aspose.slides/iaudio).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```

Aggiunge una copia di un file audio da un'altra presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio di origine. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Crea e aggiunge un audio a una presentazione da stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere l'audio. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Crea e aggiunge un audio a una presentazione da stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere l'audio. |
| loadingStreamBehavior | int | Il [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) che verrà applicato allo stream. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Crea e aggiunge un audio a una presentazione da un array di byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| audioData | byte[] | Byte audio. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
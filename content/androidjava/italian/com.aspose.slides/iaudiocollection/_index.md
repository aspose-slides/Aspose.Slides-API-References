---
title: IAudioCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una raccolta di file audio incorporati.
type: docs
url: /it/com.aspose.slides/iaudiocollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Rappresenta una raccolta di file audio incorporati.
## Metodi

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Aggiunge una copia di un file audio da un'altra presentazione. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Crea e aggiunge un audio a una presentazione dallo stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Crea e aggiunge un audio a una presentazione dallo stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Crea e aggiunge un audio a una presentazione da un array di byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```

Ottiene l'elemento all'indice specificato. Solo lettura [IAudio](../../com.aspose.slides/iaudio).

**Parametri:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio di origine. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```

Crea e aggiunge un audio a una presentazione dallo stream.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere l'audio. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Crea e aggiunge un audio a una presentazione dallo stream.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere l'audio video. |
| loadingStreamBehavior | int | Il [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) che verrà applicato allo stream. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```

Crea e aggiunge un audio a una presentazione da un array di byte.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Byte audio. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
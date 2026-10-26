---
title: IAudioCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av inbäddade ljudfiler.
type: docs
url: /sv/com.aspose.slides/iaudiocollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Representerar en samling av inbäddade ljudfiler.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Lägger till en kopia av en ljudfil från en annan presentation. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Skapar och lägger till ett ljud i en presentation från ström. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Skapar och lägger till ett ljud i en presentation från ström. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Skapar och lägger till ett ljud i en presentation från byte-array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Hämtar elementet på det angivna indexet. Endast läsning [IAudio](../../com.aspose.slides/iaudio).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Lägger till en kopia av en ljudfil från en annan presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Käll-audio. |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio) – Tillagt ljud.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


Skapar och lägger till ett ljud i en presentation från ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till ljud från. |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio) – Tillagt ljud.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Skapar och lägger till ett ljud i en presentation från ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till video-ljud från. |
| loadingStreamBehavior | int | Den [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) som kommer att tillämpas på strömmen. |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio) – Tillagt ljud.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Skapar och lägger till ett ljud i en presentation från byte-array.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| audioData | byte[] | Ljud-byte. |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio) – Tillagt ljud.
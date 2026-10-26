---
title: AudioCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av inbäddade ljudfiler.
type: docs
url: /sv/com.aspose.slides/audiocollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Representerar en samling av inbäddade ljudfiler.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar antalet ljudfiler i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Lägger till en kopia av en ljudfil från en annan presentation. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Skapar och lägger till ett ljud i en presentation från en ström. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Skapar och lägger till ett ljud i en presentation från en ström. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Skapar och lägger till ett ljud i en presentation från en byte-array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar ljud till angiven array med början från angivet index. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar en synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### size() {#size--}
```
public final int size()
```


Returnerar antalet ljudfiler i samlingen. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```


Hämtar elementet på det angivna indexet. Skrivskyddad [IAudio](../../com.aspose.slides/iaudio).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```


Lägger till en kopia av en ljudfil från en annan presentation.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Käll-audio. |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio) - Tillagt audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```


Skapar och lägger till ett ljud i en presentation från en ström.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till audio från. |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio) - Tillagt audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Skapar och lägger till ett ljud i en presentation från en ström.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till video audio från. |
| loadingStreamBehavior | int | Beteendet som kommer att tillämpas på strömmen. |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio) - Tillagt audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```


Skapar och lägger till ett ljud i en presentation från en byte-array.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Ljudbytes. |

**Returnerar:**
[IAudio](../../com.aspose.slides/iaudio) - Tillagt audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopierar ljud till angiven array med början från angivet index.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returnerar en synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - En java.util.Iterator för hela samlingen.
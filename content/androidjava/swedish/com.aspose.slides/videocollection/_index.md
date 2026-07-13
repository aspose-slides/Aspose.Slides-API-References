---
title: VideoCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av Video-objekt.
type: docs
url: /sv/com.aspose.slides/videocollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Representerar en samling av Video-objekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar antalet videofiler i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet vid angivet index. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Lägger till en kopia av en videofil från en annan presentation. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Skapar och lägger till en video i en presentation från en ström. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Skapar och lägger till en video i en presentation från en bytearray. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar videor till angiven array med start från angivet index. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar en synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### size() {#size--}
```
public final int size()
```


Returnerar antalet videofiler i samlingen. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


Hämtar elementet vid angivet index. Skrivskyddad [IVideo](../../com.aspose.slides/ivideo).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


Lägger till en kopia av en videofil från en annan presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Källvideo. |

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo) - Tillagd video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Skapar och lägger till en video i en presentation från en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till videofil från. |
| loadingStreamBehavior | int | Det beteende som kommer att tillämpas på strömmen. |

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo) - Tillagd [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


Skapar och lägger till en video i en presentation från en bytearray.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| videoData | byte[] | Video-bytes. |

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo) - Tillagd video.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopierar videor till angiven array med start från angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
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
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - En java.util.Iterator för hela samlingen.
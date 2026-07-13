---
title: IVideoCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av Video-objekt.
type: docs
url: /sv/com.aspose.slides/ivideocollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Representerar en samling av Video-objekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Lägger till en kopia av en videofil från en annan presentation. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Skapar och lägger till en video i en presentation från en ström. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Skapar och lägger till en video i en presentation från en byte-array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [IVideo](../../com.aspose.slides/ivideo).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
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
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Skapar och lägger till en video i en presentation från en ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ström att lägga till videofil från. |
| loadingStreamBehavior | int | Beteendet som ska tillämpas på strömmen. |

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo) - Tillagd [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

Skapar och lägger till en video i en presentation från en byte-array.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| videoData | byte[] | Video-bytes. |

**Returnerar:**
[IVideo](../../com.aspose.slides/ivideo) - Tillagd video.
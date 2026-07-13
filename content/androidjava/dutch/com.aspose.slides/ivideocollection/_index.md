---
title: IVideoCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling Video-objecten voor.
type: docs
url: /nl/com.aspose.slides/ivideocollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Stelt een verzameling Video-objecten voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Voegt een kopie van een videobestand toe vanuit een andere presentatie. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Maakt een video en voegt deze toe aan een presentatie vanuit een stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Maakt een video en voegt deze toe aan een presentatie vanuit een byte-array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [IVideo](../../com.aspose.slides/ivideo).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

Voegt een kopie van een videobestand toe vanuit een andere presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Bronvideo. |

**Retour:**
[IVideo](../../com.aspose.slides/ivideo) - Toegevoegde video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Maakt een video en voegt deze toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream waaruit het videobestand moet worden toegevoegd. |
| loadingStreamBehavior | int | Het gedrag dat op de stream wordt toegepast. |

**Retour:**
[IVideo](../../com.aspose.slides/ivideo) - Toegevoegd [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

Maakt een video en voegt deze toe aan een presentatie vanuit een byte-array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| videoData | byte[] | Videobytes. |

**Retour:**
[IVideo](../../com.aspose.slides/ivideo) - Toegevoegde video.
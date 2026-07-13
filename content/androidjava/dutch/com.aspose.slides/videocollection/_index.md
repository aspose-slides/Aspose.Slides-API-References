---
title: VideoCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van Video-objecten voor.
type: docs
url: /nl/com.aspose.slides/videocollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Stelt een collectie van Video-objecten voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert een aantal videobestanden in de collectie. |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Voegt een kopie van een videobestand toe van een andere presentatie. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Maakt een video aan en voegt deze toe aan een presentatie vanuit een stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Maakt een video aan en voegt deze toe aan een presentatie vanuit een byte-array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert video's naar een opgegeven array beginnend vanaf een opgegeven index. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatie-root. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereren. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
### size() {#size--}
```
public final int size()
```

Retourneert een aantal videobestanden in de collectie. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
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
public final IVideo addVideo(IVideo video)
```

Voegt een kopie van een videobestand toe van een andere presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Bron-video. |

**Retour:**
[IVideo](../../com.aspose.slides/ivideo) - Toegevoegde video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Maakt een video aan en voegt deze toe aan een presentatie vanuit een stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Stream waaruit het videobestand moet worden toegevoegd. |
| loadingStreamBehavior | int | Het gedrag dat op de stream zal worden toegepast. |

**Retour:**
[IVideo](../../com.aspose.slides/ivideo) - Toegevoegd [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Maakt een video aan en voegt deze toe aan een presentatie vanuit een byte-array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| videoData | byte[] | Video-bytes. |

**Retour:**
[IVideo](../../com.aspose.slides/ivideo) - Toegevoegde video.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert video's naar de opgegeven array beginnend vanaf de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatie-root. Alleen-lezen Object.

**Retour:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Retourneert een enumerator die door de collectie itereren.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Een java.util.Iterator voor de volledige collectie.
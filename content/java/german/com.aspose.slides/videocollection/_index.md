---
title: VideoCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Videoobjekten dar.
type: docs
url: /de/com.aspose.slides/videocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Represents a collection of Video objects.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Returns a number of video files in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Adds a copy of an video file from an another presentation. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Creates and adds a video to a presentation from stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Creates and adds a video to a presentation from byte array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies videos to specified array starting from specified index. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Videodateien in der Sammlung zurück. Nur lesender int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur lesend [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Quellvideo. |

**Rückgabe:**
[IVideo](../../com.aspose.slides/ivideo) - Hinzugefügtes Video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Erstellt und fügt ein Video aus einem Stream zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem die Videodatei hinzugefügt wird. |
| loadingStreamBehavior | int | Das Verhalten, das auf den Stream angewendet wird. |

**Rückgabe:**
[IVideo](../../com.aspose.slides/ivideo) - Hinzugefügt [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Erstellt und fügt ein Video aus einem Byte-Array zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| videoData | byte[] | Video-Bytes. |

**Rückgabe:**
[IVideo](../../com.aspose.slides/ivideo) - Hinzugefügtes Video.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert Videos in das angegebene Array, beginnend ab dem angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-safe) ist. Nur lesendes boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt die Synchronisationswurzel zurück. Nur lesendes Object.

**Rückgabe:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Ein java.util.Iterator für die gesamte Sammlung.
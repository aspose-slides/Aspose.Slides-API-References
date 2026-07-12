---
title: VideoCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Video-Objekten dar.
type: docs
url: /de/com.aspose.slides/videocollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Stellt eine Sammlung von Video-Objekten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Videodateien in der Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Erstellt und fügt ein Video zu einer Präsentation aus einem Stream hinzu. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Erstellt und fügt ein Video zu einer Präsentation aus einem Byte-Array hinzu. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert Videos in ein angegebenes Array, beginnend am angegebenen Index. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Videodateien in der Sammlung zurück. Nur lesbar int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur lesbar [IVideo](../../com.aspose.slides/ivideo).

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

Erstellt und fügt ein Video zu einer Präsentation aus einem Stream hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem die Videodatei hinzugefügt wird. |
| loadingStreamBehavior | int | Das Verhalten, das auf den Stream angewendet wird. |

**Rückgabe:**
[IVideo](../../com.aspose.slides/ivideo) - Hinzugefügtes [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Erstellt und fügt ein Video zu einer Präsentation aus einem Byte-Array hinzu.

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

Kopiert Videos in ein angegebenes Array, beginnend am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesbar boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt die Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabe:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Ein java.util.Iterator für die gesamte Sammlung.
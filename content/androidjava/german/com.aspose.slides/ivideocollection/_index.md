---
title: IVideoCollection
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Sammlung von Video-Objekten dar.
type: docs
url: /de/com.aspose.slides/ivideocollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Stellt eine Sammlung von Video-Objekten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Erstellt und fügt ein Video einer Präsentation aus einem Stream hinzu. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Erstellt und fügt ein Video einer Präsentation aus einem Byte-Array hinzu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur lesbar [IVideo](../../com.aspose.slides/ivideo).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```

Fügt eine Kopie einer Videodatei aus einer anderen Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Quellvideo. |

**Rückgabewert:**
[IVideo](../../com.aspose.slides/ivideo) - Hinzugefügtes Video.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Erstellt und fügt ein Video einer Präsentation aus einem Stream hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem die Videodatei hinzugefügt wird. |
| loadingStreamBehavior | int | Das Verhalten, das auf den Stream angewendet wird. |

**Rückgabewert:**
[IVideo](../../com.aspose.slides/ivideo) - Hinzugefügt [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```

Erstellt und fügt ein Video einer Präsentation aus einem Byte-Array hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| videoData | byte[] | Video-Bytes. |

**Rückgabewert:**
[IVideo](../../com.aspose.slides/ivideo) - Hinzugefügtes Video.
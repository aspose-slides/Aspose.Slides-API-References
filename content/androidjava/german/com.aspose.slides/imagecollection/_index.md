---
title: ImageCollection
second_title: Aspose.Slides für Android via Java API-Referenz
description: Stellt eine Sammlung von PPImage dar.
type: docs
url: /de/com.aspose.slides/imagecollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

Stellt eine Sammlung von PPImage dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Bilder in der Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Fügt ein Bild zu einer Präsentation hinzu. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Fügt ein Bild zu einer Präsentation aus einem Stream hinzu. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Erstellt und fügt ein Bild zu einer Präsentation aus einem Stream hinzu. |
| [addImage(byte[] buffer)](#addImage-byte---) | Fügt ein Bild zu einer Präsentation aus dem angegebenen Puffer hinzu. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Fügt ein Bild zu einer Präsentation aus einem Svg-Objekt hinzu. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-safe) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Bilder in der Sammlung zurück. Nur lesbar  int .

**Rückgabewert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur lesbar [IPPImage](../../com.aspose.slides/ippimage).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```


Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Quellbild. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) – Hinzugefügtes Bild.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```


Fügt ein Bild zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Hinzuzufügendes Bild.

--------------------

Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild, bevor sie in eine Präsentation eingefügt wird. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) – Hinzugefügtes Bild.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```


Fügt ein Bild zu einer Präsentation aus einem Stream hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem das Bild hinzugefügt wird.

--------------------

Diese Methode kann WMF/EMF-Metadateien zu einer Präsentation hinzufügen, ohne sie in ein Raster-PNG-Bild zu konvertieren. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) – Hinzugefügtes Bild.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Erstellt und fügt ein Bild zu einer Präsentation aus einem Stream hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem die Bilddatei hinzugefügt wird. |
| loadingStreamBehavior | int | Das Verhalten, das auf den Stream angewendet wird. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) – Hinzugefügtes [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```


Fügt ein Bild zu einer Präsentation aus dem angegebenen Puffer hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | byte[] | Puffer. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) – Hinzugefügtes Bild.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```


Fügt ein Bild zu einer Präsentation aus einem Svg-Objekt hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Svg-Bildobjekt [ISvgImage](../../com.aspose.slides/isvgimage) |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) – Hinzugefügtes Bild.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> – Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> – Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-safe) ist. Nur lesbar  boolean .

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt die Synchronisationswurzel zurück. Nur lesbar  Object .

**Rückgabewert:**
java.lang.Object
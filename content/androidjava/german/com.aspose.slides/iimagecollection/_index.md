---
title: IImageCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von PPImage dar.
type: docs
url: /de/com.aspose.slides/iimagecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Stellt eine Sammlung von PPImage dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Bild anhand seines Index zurück. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Fügt ein Bild zu einer Präsentation hinzu. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Fügt ein Bild aus einem Stream zu einer Präsentation hinzu. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Erstellt und fügt ein Bild aus einem Stream zu einer Präsentation hinzu. |
| [addImage(byte[] buffer)](#addImage-byte---) | Fügt ein Bild aus einem angegebenen Puffer zu einer Präsentation hinzu. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Fügt ein Bild aus einem SVG-Objekt zu einer Präsentation hinzu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Gibt das Bild anhand seines Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Fügt ein Bild zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Bild, das hinzugefügt werden soll.

--------------------

Diese Methode konvertiert WMF/EMF-Metadateien in ein Raster-PNG-Bild, bevor sie in eine Präsentation eingefügt wird. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) - Hinzugefügtes Bild.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Fügt ein Bild aus einem Stream zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem das Bild hinzugefügt werden soll.

--------------------

Diese Methode kann WMF/EMF-Metadateien zu einer Präsentation hinzufügen, ohne sie in ein Raster-PNG-Bild zu konvertieren. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) - Hinzugefügtes Bild.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Erstellt und fügt ein Bild aus einem Stream zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | java.io.InputStream | Stream, aus dem die Bilddatei hinzugefügt werden soll. |
| loadingStreamBehavior | int | Das Verhalten, das auf den Stream angewendet wird. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) - Hinzugefügt [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Fügt ein Bild aus einem angegebenen Puffer zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | byte[] | Puffer. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) - Hinzugefügtes Bild.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Fügt eine Kopie eines Bildes aus einer anderen Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Quellbild. |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) - Hinzugefügtes Bild.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Fügt ein Bild aus einem SVG-Objekt zu einer Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | SVG-Bildobjekt [ISvgImage](../../com.aspose.slides/isvgimage) |

**Rückgabewert:**
[IPPImage](../../com.aspose.slides/ippimage) - Hinzugefügtes Bild.
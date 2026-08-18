---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: Represents an image in a presentation.
type: docs
url: /de/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Stellt ein Bild in einer Präsentation dar.
## Methoden

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Gibt eine Kopie der Bilddaten zurück. |
| [getImage()](#getImage--) | Gibt eine Kopie des Bildes zurück. |
| [getSvgImage()](#getSvgImage--) | Gibt ein ISvgImage-Objekt zurück oder setzt es [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Gibt ein ISvgImage-Objekt zurück oder setzt es [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Ersetzt Bilddaten. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Ersetzt das Bild. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Ersetzt das Bild. |
| [getContentType()](#getContentType--) | Gibt den MIME-Typ eines Bildes zurück, codiert in \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Gibt die Breite eines Bildes zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe eines Bildes zurück. |
| [getX()](#getX--) | Gibt den X-Offset eines Bildes zurück. |
| [getY()](#getY--) | Gibt den Y-Offset eines Bildes zurück. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Gibt eine Kopie der Bilddaten zurück. Nur lesbar byte[].

**Rückgabe:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Gibt eine Kopie des Bildes zurück. Nur lesbar \#getImage.getImage.

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Gibt ein ISvgImage-Objekt zurück oder setzt es [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Dieser Wert zeigt an, dass dieses Bild aus SVG erstellt wurde.

**Rückgabe:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


Gibt ein ISvgImage-Objekt zurück oder setzt es [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Dieser Wert zeigt an, dass dieses Bild aus SVG erstellt wurde.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```


Ersetzt Bilddaten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newImageData | byte[] | Die Daten des neuen Bildes. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Ersetzt das Bild. Hinweis: wenn das Bild eine Metadatei ist, wird es rasterisiert. Verwenden Sie stattdessen replaceImage(byte[]) .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Das neue Bild. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Ersetzt das Bild.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Das neue IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Gibt den MIME-Typ eines Bildes zurück, codiert in \#getBinaryData.getBinaryData. Nur lesbar String.

**Rückgabe:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Gibt die Breite eines Bildes zurück. Nur lesbar int.

**Rückgabe:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Gibt die Höhe eines Bildes zurück. Nur lesbar int.

**Rückgabe:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Gibt den X-Offset eines Bildes zurück. Nur lesbar int.

**Rückgabe:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Gibt den Y-Offset eines Bildes zurück. Nur lesbar int.

**Rückgabe:**
int
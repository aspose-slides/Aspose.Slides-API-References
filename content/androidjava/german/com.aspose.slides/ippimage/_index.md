---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an image in a presentation.
type: docs
url: /de/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Stellt ein Bild in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Gibt eine Kopie der Bilddaten zurück. |
| [getImage()](#getImage--) | Gibt eine Kopie des Bildes zurück. |
| [getSvgImage()](#getSvgImage--) | Gibt zurück oder setzt ISvgImage-Objekt [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Gibt zurück oder setzt ISvgImage-Objekt [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Ersetzt Bilddaten. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Ersetzt das Bild. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Ersetzt das Bild. |
| [getContentType()](#getContentType--) | Gibt den MIME-Typ eines Bildes zurück, codiert in \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Gibt die Breite eines Bildes zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe eines Bildes zurück. |
| [getX()](#getX--) | Gibt den X-Versatz eines Bildes zurück. |
| [getY()](#getY--) | Gibt den Y-Versatz eines Bildes zurück. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Gibt eine Kopie der Bilddaten zurück. Nur lesend byte[].

**Rückgabe:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Gibt eine Kopie des Bildes zurück. Nur lesend \#getImage.getImage.

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

Gibt zurück oder setzt ISvgImage-Objekt [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Dieser Wert gibt an, dass dieses Bild aus SVG erstellt wurde.

**Rückgabe:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Gibt zurück oder setzt ISvgImage-Objekt [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Dieser Wert gibt an, dass dieses Bild aus SVG erstellt wurde.

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

Ersetzt das Bild. Hinweis: Wenn das Bild ein Metafile ist, wird es gerastert. Verwenden Sie stattdessen replaceImage(byte[]).

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

Gibt den MIME-Typ eines Bildes zurück, codiert in \#getBinaryData.getBinaryData. Nur lesend String.

**Rückgabe:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Gibt die Breite eines Bildes zurück. Nur lesend int.

**Rückgabe:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Gibt die Höhe eines Bildes zurück. Nur lesend int.

**Rückgabe:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Gibt den X-Versatz eines Bildes zurück. Nur lesend int.

**Rückgabe:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Gibt den Y-Versatz eines Bildes zurück. Nur lesend int.

**Rückgabe:**
int
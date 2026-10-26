---
title: PPImage
second_title: Aspose.Slides fuer Android via Java API Referenz
description: Stellt ein Bild in einer Praesentation dar.
type: docs
url: /de/com.aspose.slides/ppimage/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Stellt ein Bild in einer Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Gibt eine Kopie der Bilddaten zurück. |
| [getImage()](#getImage--) | Gibt eine Kopie des Bildes zurück. |
| [getSvgImage()](#getSvgImage--) | Gibt das ISvgImage-Objekt zurück oder setzt es [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Gibt das ISvgImage-Objekt zurück oder setzt es [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Ersetzt Bilddaten. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Ersetzt Bilddaten. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Ersetzt Bilddaten. |
| [getContentType()](#getContentType--) | Gibt den MIME-Typ eines Bildes zurück, kodiert in BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Gibt die Breite eines Bildes zurück. |
| [getHeight()](#getHeight--) | Gibt die Höhe eines Bildes zurück. |
| [getX()](#getX--) | Gibt den X-Offset eines Bildes zurück. |
| [getY()](#getY--) | Gibt den Y-Offset eines Bildes zurück. |
| [hashCode()](#hashCode--) | Gibt den Hashcode eines Bildes zurück. |
| [dispose()](#dispose--) | Gibt das Objekt frei. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Gibt eine Kopie der Bilddaten zurück. Nur lesbar  byte[] .

**Rückgabe:**
byte[] - Array von Bytes
### getImage() {#getImage--}
```
public final IImage getImage()
```

Gibt eine Kopie des Bildes zurück. Nur lesbar [IImage](../../com.aspose.slides/iimage).

**Rückgabe:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

Gibt das ISvgImage-Objekt zurück oder setzt es [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Dieser Wert zeigt an, dass dieses Bild aus SVG erstellt wurde.

**Rückgabe:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

Gibt das ISvgImage-Objekt zurück oder setzt es [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Dieser Wert zeigt an, dass dieses Bild aus SVG erstellt wurde.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

Ersetzt Bilddaten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newImageData | byte[] | Die Daten des neuen Bildes. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

Ersetzt Bilddaten. Achtung: Wenn das Bild ein Metafile ist, wird es gerastert. Verwenden Sie stattdessen ReplaceImage(byte[]).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Das neue Bild. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

Ersetzt Bilddaten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Das neue IPPImage. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

Gibt den MIME-Typ eines Bildes zurück, kodiert in BinaryData (\#getBinaryData.getBinaryData). Nur lesbar String.

**Rückgabe:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

Gibt die Breite eines Bildes zurück. Nur lesbar  int .

**Rückgabe:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

Gibt die Höhe eines Bildes zurück. Nur lesbar  int .

**Rückgabe:**
int
### getX() {#getX--}
```
public final int getX()
```

Gibt den X-Offset eines Bildes zurück. Nur lesbar  int .

**Rückgabe:**
int
### getY() {#getY--}
```
public final int getY()
```

Gibt den Y-Offset eines Bildes zurück. Nur lesbar  int .

**Rückgabe:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

Gibt den Hashcode eines Bildes zurück.

**Rückgabe:**
int - Hashcode.
### dispose() {#dispose--}
```
public final void dispose()
```

Gibt das Objekt frei.
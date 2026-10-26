---
title: IPPImage
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en bild i en presentation.
type: docs
url: /sv/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Representerar en bild i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Returnerar en kopia av en bilds data. |
| [getImage()](#getImage--) | Returnerar en kopia av en bild. |
| [getSvgImage()](#getSvgImage--) | Returnerar eller sätter ISvgImage-objekt [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Returnerar eller sätter ISvgImage-objekt [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Ersätter bilddata. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Ersätter bild. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Ersätter bild. |
| [getContentType()](#getContentType--) | Returnerar en MIME-typ för en bild, kodad i \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Returnerar bredden på en bild. |
| [getHeight()](#getHeight--) | Returnerar höjden på en bild. |
| [getX()](#getX--) | Returnerar en X-offset för en bild. |
| [getY()](#getY--) | Returnerar en Y-offset för en bild. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Returnerar en kopia av en bilds data. Läs-endast byte[].

**Returnerar:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Returnerar en kopia av en bild. Läs-endast \#getImage.getImage.

**Returnerar:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Returnerar eller sätter ISvgImage-objekt [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Detta värde indikerar att denna bild har skapats från SVG.

**Returnerar:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


Returnerar eller sätter ISvgImage-objekt [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Detta värde indikerar att denna bild har skapats från SVG.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```


Ersätter bilddata.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newImageData | byte[] | Den nya bildens data. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Ersätter bild. Attention: when Image is metafile - it will be rasterized. Use replaceImage(byte[]) instead

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Den nya bilden. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Ersätter bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Den nya IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Returnerar en MIME-typ för en bild, kodad i \#getBinaryData.getBinaryData. Läs-endast String.

**Returnerar:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Returnerar bredden på en bild. Läs-endast int.

**Returnerar:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Returnerar höjden på en bild. Läs-endast int.

**Returnerar:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Returnerar en X-offset för en bild. Läs-endast int.

**Returnerar:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Returnerar en Y-offset för en bild. Läs-endast int.

**Returnerar:**
int
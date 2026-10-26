---
title: PPImage
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en bild i en presentation.
type: docs
url: /sv/com.aspose.slides/ppimage/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Representerar en bild i en presentation.
## Metoder

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Returnerar en kopia av en bilds data. |
| [getImage()](#getImage--) | Returnerar en kopia av en bild. |
| [getSvgImage()](#getSvgImage--) | Returnerar eller sätter ISvgImage-objekt [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Returnerar eller sätter ISvgImage-objekt [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Ersätter bilddata. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Ersätter bilddata. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Ersätter bilddata. |
| [getContentType()](#getContentType--) | Returnerar en MIME-typ för en bild, kodad i BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Returnerar bildens bredd. |
| [getHeight()](#getHeight--) | Returnerar bildens höjd. |
| [getX()](#getX--) | Returnerar en X-förskjutning för en bild. |
| [getY()](#getY--) | Returnerar en Y-förskjutning för en bild. |
| [hashCode()](#hashCode--) | Returnerar bildens hashkod. |
| [dispose()](#dispose--) | Frigör objektet. |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

Returnerar en kopia av en bilds data. Skrivskyddad  byte[] .

**Returnerar:**
byte[] - Array av byte

### getImage() {#getImage--}
```
public final IImage getImage()
```

Returnerar en kopia av en bild. Skrivskyddad [IImage](../../com.aspose.slides/iimage).

**Returnerar:**
[IImage](../../com.aspose.slides/iimage)

### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

Returnerar eller sätter ISvgImage-objekt [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Detta värde indikerar att denna bild har skapats från SVG.

**Returnerar:**
[ISvgImage](../../com.aspose.slides/isvgimage)

### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
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
public final void replaceImage(byte[] newImageData)
```

Ersätter bilddata.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newImageData | byte[] | Den nya bildens data. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

Ersätter bilddata. Obs: när Image är metafil – den kommer att rasteriseras. Använd ReplaceImage(byte[]) istället

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | Den nya bilden. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

Ersätter bilddata.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Den nya IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Returnerar en MIME-typ för en bild, kodad i BinaryData (\#getBinaryData.getBinaryData). Skrivskyddad String.

**Returnerar:**
java.lang.String

### getWidth() {#getWidth--}
```
public final int getWidth()
```

Returnerar bildens bredd. Skrivskyddad  int .

**Returnerar:**
int

### getHeight() {#getHeight--}
```
public final int getHeight()
```

Returnerar bildens höjd. Skrivskyddad  int .

**Returnerar:**
int

### getX() {#getX--}
```
public final int getX()
```

Returnerar en X-förskjutning för en bild. Skrivskyddad  int .

**Returnerar:**
int

### getY() {#getY--}
```
public final int getY()
```

Returnerar en Y-förskjutning för en bild. Skrivskyddad  int .

**Returnerar:**
int

### hashCode() {#hashCode--}
```
public int hashCode()
```

Returnerar bildens hashkod.

**Returnerar:**
int - Hashkod.

### dispose() {#dispose--}
```
public final void dispose()
```

Frigör objektet.
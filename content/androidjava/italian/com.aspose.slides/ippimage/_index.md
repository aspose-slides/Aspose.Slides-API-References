---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an image in a presentation.
type: docs
url: /it/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Represents an image in a presentation.
## Metodi

| Method | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Restituisce una copia dei dati di un'immagine. |
| [getImage()](#getImage--) | Restituisce una copia di un'immagine. |
| [getSvgImage()](#getSvgImage--) | Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Sostituisce i dati dell'immagine. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Sostituisce l'immagine. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Sostituisce l'immagine. |
| [getContentType()](#getContentType--) | Restituisce un tipo MIME di un'immagine, codificato in \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Restituisce la larghezza di un'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza di un'immagine. |
| [getX()](#getX--) | Restituisce l'offset X di un'immagine. |
| [getY()](#getY--) | Restituisce l'offset Y di un'immagine. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

Restituisce una copia dei dati di un'immagine. Solo lettura byte[].

**Restituisce:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Restituisce una copia di un'immagine. Solo lettura \#getImage.getImage.

**Restituisce:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Questo valore indica che quest'immagine è stata creata da SVG.

**Restituisce:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Questo valore indica che quest'immagine è stata creata da SVG.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```

Sostituisce i dati dell'immagine.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | I dati della nuova immagine. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```

Sostituisce l'immagine. Attenzione: quando l'Image è un metafile - verrà rasterizzata. Usa replaceImage(byte[]) invece

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | La nuova immagine. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```

Sostituisce l'immagine.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Il nuovo IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Restituisce un tipo MIME di un'immagine, codificato in \#getBinaryData.getBinaryData. Solo lettura String.

**Restituisce:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Restituisce la larghezza di un'immagine. Solo lettura int.

**Restituisce:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Restituisce l'altezza di un'immagine. Solo lettura int.

**Restituisce:**
int
### getX() {#getX--}
```
public abstract int getX()
```

Restituisce l'offset X di un'immagine. Solo lettura int.

**Restituisce:**
int
### getY() {#getY--}
```
public abstract int getY()
```

Restituisce l'offset Y di un'immagine. Solo lettura int.

**Restituisce:**
int
---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un'immagine in una presentazione.
type: docs
url: /it/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Rappresenta un'immagine in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Restituisce una copia dei dati dell'immagine. |
| [getImage()](#getImage--) | Restituisce una copia di un'immagine. |
| [getSvgImage()](#getSvgImage--) | Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Sostituisce i dati dell'immagine. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Sostituisce l'immagine. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Sostituisce l'immagine. |
| [getContentType()](#getContentType--) | Restituisce un tipo MIME di un'immagine, codificato in \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Restituisce la larghezza di un'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza di un'immagine. |
| [getX()](#getX--) | Restituisce un offset X di un'immagine. |
| [getY()](#getY--) | Restituisce un offset Y di un'immagine. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Restituisce una copia dei dati dell'immagine. Sola lettura byte[].

**Returns:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Restituisce una copia di un'immagine. Sola lettura \#getImage.getImage.

**Returns:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Questo valore indica che questa immagine è stata creata da SVG.

**Returns:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


Restituisce o imposta l'oggetto ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Questo valore indica che questa immagine è stata creata da SVG.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```


Sostituisce i dati dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newImageData | byte[] | I dati della nuova immagine. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Sostituisce l'immagine. Attenzione: quando l'Image è metafile - verrà rasterizzata. Usa replaceImage(byte[]) invece

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | La nuova immagine. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Sostituisce l'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Il nuovo IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Restituisce un tipo MIME di un'immagine, codificato in \#getBinaryData.getBinaryData. Sola lettura String.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Restituisce la larghezza di un'immagine. Sola lettura int.

**Returns:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Restituisce l'altezza di un'immagine. Sola lettura int.

**Returns:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Restituisce un offset X di un'immagine. Sola lettura int.

**Returns:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Restituisce un offset Y di un'immagine. Sola lettura int.

**Returns:**
int
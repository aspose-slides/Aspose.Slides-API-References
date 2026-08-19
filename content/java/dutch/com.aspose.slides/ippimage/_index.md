---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: Represents an image in a presentation.
type: docs
url: /nl/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Stelt een afbeelding in een presentatie voor.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Retourneert een kopie van de gegevens van een afbeelding. |
| [getImage()](#getImage--) | Retourneert een kopie van een afbeelding. |
| [getSvgImage()](#getSvgImage--) | Retourneert of stelt ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Retourneert of stelt ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Vervangt afbeeldingsgegevens. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Vervangt afbeelding. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Vervangt afbeelding. |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een afbeelding, gecodeerd in \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Retourneert een breedte van een afbeelding. |
| [getHeight()](#getHeight--) | Retourneert een hoogte van een afbeelding. |
| [getX()](#getX--) | Retourneert een X-offset van een afbeelding. |
| [getY()](#getY--) | Retourneert een Y-offset van een afbeelding. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Retourneert een kopie van de gegevens van een afbeelding. Alleen-lezen byte[].

**Retourneert:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Retourneert een kopie van een afbeelding. Alleen-lezen \#getImage.getImage.

**Retourneert:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Retourneert of stelt ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Deze waarde geeft aan dat deze afbeelding is gemaakt vanuit SVG.

**Retourneert:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


Retourneert of stelt ISvgImage object [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Deze waarde geeft aan dat deze afbeelding is gemaakt vanuit SVG.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```


Vervangt afbeeldingsgegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newImageData | byte[] | De nieuwe afbeeldingsgegevens. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Vervangt afbeelding. Let op: wanneer Image een metafile is - wordt deze gerasterd. Gebruik replaceImage(byte[]) in plaats daarvan

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | De nieuwe afbeelding. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Vervangt afbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | De nieuwe IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Retourneert een MIME-type van een afbeelding, gecodeerd in \#getBinaryData.getBinaryData. Alleen-lezen String.

**Retourneert:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Retourneert een breedte van een afbeelding. Alleen-lezen int.

**Retourneert:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Retourneert een hoogte van een afbeelding. Alleen-lezen int.

**Retourneert:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Retourneert een X-offset van een afbeelding. Alleen-lezen int.

**Retourneert:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Retourneert een Y-offset van een afbeelding. Alleen-lezen int.

**Retourneert:**
int
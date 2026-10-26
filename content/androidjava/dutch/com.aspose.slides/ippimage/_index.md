---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een afbeelding in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Stelt een afbeelding in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Retourneert een kopie van de data van een afbeelding. |
| [getImage()](#getImage--) | Retourneert een kopie van een afbeelding. |
| [getSvgImage()](#getSvgImage--) | Retourneert of stelt ISvgImage-object [ISvgImage](../../com.aspose.slides/isvgimage) in |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Retourneert of stelt ISvgImage-object [ISvgImage](../../com.aspose.slides/isvgimage) in |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Vervangt afbeeldingsdata. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Vervangt afbeelding. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Vervangt afbeelding. |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een afbeelding, gecodeerd in \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Retourneert de breedte van een afbeelding. |
| [getHeight()](#getHeight--) | Retourneert de hoogte van een afbeelding. |
| [getX()](#getX--) | Retourneert een X-offset van een afbeelding. |
| [getY()](#getY--) | Retourneert een Y-offset van een afbeelding. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Retourneert een kopie van de data van een afbeelding. Alleen-lezen byte[].

**Retour:**  
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Retourneert een kopie van een afbeelding. Alleen-lezen \#getImage.getImage.

**Retour:**  
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Retourneert of stelt ISvgImage-object [ISvgImage](../../com.aspose.slides/isvgimage) in

--------------------

Deze waarde geeft aan dat deze afbeelding is gemaakt vanuit SVG.

**Retour:**  
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


Retourneert of stelt ISvgImage-object [ISvgImage](../../com.aspose.slides/isvgimage) in

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


Vervangt afbeeldingsdata.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newImageData | byte[] | De data van de nieuwe afbeelding. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Vervangt afbeelding. Let op: wanneer Image een metabestand is, wordt deze gerasterd. Gebruik replaceImage(byte[]) in plaats daarvan

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

**Retour:**  
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Retourneert de breedte van een afbeelding. Alleen-lezen int.

**Retour:**  
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Retourneert de hoogte van een afbeelding. Alleen-lezen int.

**Retour:**  
int
### getX() {#getX--}
```
public abstract int getX()
```


Retourneert een X-offset van een afbeelding. Alleen-lezen int.

**Retour:**  
int
### getY() {#getY--}
```
public abstract int getY()
```


Retourneert een Y-offset van een afbeelding. Alleen-lezen int.

**Retour:**  
int
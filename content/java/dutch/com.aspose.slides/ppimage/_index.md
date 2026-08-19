---
title: PPImage
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een afbeelding in een presentatie voor.
type: docs
url: /nl/com.aspose.slides/ppimage/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

Stelt een afbeelding in een presentatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Retourneert een kopie van de gegevens van een afbeelding. |
| [getImage()](#getImage--) | Retourneert een kopie van een afbeelding. |
| [getSvgImage()](#getSvgImage--) | Retourneert of stelt ISvgImage-object [ISvgImage](../../com.aspose.slides/isvgimage) in. |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Retourneert of stelt ISvgImage-object [ISvgImage](../../com.aspose.slides/isvgimage) in. |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Vervangt afbeeldingsgegevens. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Vervangt afbeeldingsgegevens. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Vervangt afbeeldingsgegevens. |
| [getContentType()](#getContentType--) | Retourneert een MIME-type van een afbeelding, gecodeerd in  BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Retourneert een breedte van een afbeelding. |
| [getHeight()](#getHeight--) | Retourneert een hoogte van een afbeelding. |
| [getX()](#getX--) | Retourneert een X-offset van een afbeelding. |
| [getY()](#getY--) | Retourneert een Y-offset van een afbeelding. |
| [hashCode()](#hashCode--) | Retourneert de hashcode van een afbeelding. |
| [dispose()](#dispose--) | Verwijdert het object. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Retourneert een kopie van de gegevens van een afbeelding. Alleen-lezen  byte[] .

**Retour:**
byte[] - Array van bytes
### getImage() {#getImage--}
```
public final IImage getImage()
```


Retourneert een kopie van een afbeelding. Alleen-lezen [IImage](../../com.aspose.slides/iimage).

**Retour:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Retourneert of stelt ISvgImage-object [ISvgImage](../../com.aspose.slides/isvgimage) in.

--------------------

Deze waarde geeft aan dat deze afbeelding is gemaakt vanuit SVG.

**Retour:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


Retourneert of stelt ISvgImage-object [ISvgImage](../../com.aspose.slides/isvgimage) in.

--------------------

Deze waarde geeft aan dat deze afbeelding is gemaakt vanuit SVG.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Vervangt afbeeldingsgegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newImageData | byte[] | De gegevens van de nieuwe afbeelding. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Vervangt afbeeldingsgegevens. Let op: wanneer Image een metafile is - wordt deze gerasterd. Gebruik ReplaceImage(byte[]) in plaats daarvan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | De nieuwe afbeelding. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Vervangt afbeeldingsgegevens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | De nieuwe IPPImage. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```


Retourneert een MIME-type van een afbeelding, gecodeerd in  BinaryData (\#getBinaryData.getBinaryData). Alleen-lezen String.

**Retour:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Retourneert een breedte van een afbeelding. Alleen-lezen  int .

**Retour:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Retourneert een hoogte van een afbeelding. Alleen-lezen  int .

**Retour:**
int
### getX() {#getX--}
```
public final int getX()
```


Retourneert een X-offset van een afbeelding. Alleen-lezen  int .

**Retour:**
int
### getY() {#getY--}
```
public final int getY()
```


Retourneert een Y-offset van een afbeelding. Alleen-lezen  int .

**Retour:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode van een afbeelding.

**Retour:**
int - Hashcode.
### dispose() {#dispose--}
```
public final void dispose()
```


Verwijdert het object.
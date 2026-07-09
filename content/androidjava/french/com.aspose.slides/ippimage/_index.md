---
title: IPPImage
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une image dans une présentation.
type: docs
url: /fr/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Représente une image dans une présentation.
## Methods

| Méthode | Description |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | Renvoie une copie des données d'une image. |
| [getImage()](#getImage--) | Renvoie une copie d'une image. |
| [getSvgImage()](#getSvgImage--) | Renvoie ou définit l'objet ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | Renvoie ou définit l'objet ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | Remplace les données de l'image. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Remplace l'image. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Remplace l'image. |
| [getContentType()](#getContentType--) | Renvoie un type MIME d'une image, encodé dans \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | Renvoie la largeur d'une image. |
| [getHeight()](#getHeight--) | Renvoie la hauteur d'une image. |
| [getX()](#getX--) | Renvoie le décalage X d'une image. |
| [getY()](#getY--) | Renvoie le décalage Y d'une image. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Renvoie une copie des données d'une image. Lecture seule byte[].

**Returns:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Renvoie une copie d'une image. Lecture seule \#getImage.getImage.

**Returns:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Renvoie ou définit l'objet ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Cette valeur indique que cette image a été créée à partir de SVG.

**Returns:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


Renvoie ou définit l'objet ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Cette valeur indique que cette image a été créée à partir de SVG.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |

### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```


Remplace les données de l'image.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | Les nouvelles données de l'image. |

### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


Remplace l'image. Attention : lorsque l'image est un métafichier, elle sera rasterisée. Utilisez replaceImage(byte[]) à la place

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | La nouvelle image. |

### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


Remplace l'image.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | La nouvelle IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Renvoie un type MIME d'une image, encodé dans \#getBinaryData.getBinaryData. Lecture seule String.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Renvoie la largeur d'une image. Lecture seule int.

**Returns:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Renvoie la hauteur d'une image. Lecture seule int.

**Returns:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Renvoie le décalage X d'une image. Lecture seule int.

**Returns:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Renvoie le décalage Y d'une image. Lecture seule int.

**Returns:**
int
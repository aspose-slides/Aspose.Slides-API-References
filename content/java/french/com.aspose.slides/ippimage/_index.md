---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: Représente une image dans une présentation.
type: docs
url: /fr/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

Représente une image dans une présentation.
## Méthodes

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
| [getWidth()](#getWidth--) | Renvoie une largeur d'une image. |
| [getHeight()](#getHeight--) | Renvoie une hauteur d'une image. |
| [getX()](#getX--) | Renvoie un décalage X d'une image. |
| [getY()](#getY--) | Renvoie un décalage Y d'une image. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


Renvoie une copie des données d'une image. Lecture seule byte[].

**Renvoie:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Renvoie une copie d'une image. Lecture seule \#getImage.getImage.

**Renvoie:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


Renvoie ou définit l'objet ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Cette valeur indique que cette image a été créée à partir de SVG.

**Renvoie:**
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
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Le nouveau IPPImage. |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


Renvoie un type MIME d'une image, encodé dans \#getBinaryData.getBinaryData. Lecture seule String.

**Renvoie:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Renvoie une largeur d'une image. Lecture seule int.

**Renvoie:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Renvoie une hauteur d'une image. Lecture seule int.

**Renvoie:**
int
### getX() {#getX--}
```
public abstract int getX()
```


Renvoie un décalage X d'une image. Lecture seule int.

**Renvoie:**
int
### getY() {#getY--}
```
public abstract int getY()
```


Renvoie un décalage Y d'une image. Lecture seule int.

**Renvoie:**
int
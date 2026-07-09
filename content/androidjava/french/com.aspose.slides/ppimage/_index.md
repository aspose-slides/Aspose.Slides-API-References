---
title: PPImage
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une image dans une présentation.
type: docs
url: /fr/com.aspose.slides/ppimage/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
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
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | Remplace les données de l'image. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | Remplace les données de l'image. |
| [getContentType()](#getContentType--) | Renvoie un type MIME d'une image, encodé dans  BinaryData (\#getBinaryData.getBinaryData). |
| [getWidth()](#getWidth--) | Renvoie la largeur d'une image. |
| [getHeight()](#getHeight--) | Renvoie la hauteur d'une image. |
| [getX()](#getX--) | Renvoie le décalage X d'une image. |
| [getY()](#getY--) | Renvoie le décalage Y d'une image. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage d'une image. |
| [dispose()](#dispose--) | Libère l'objet. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Renvoie une copie des données d'une image. Lecture seule  byte[] .

**Returns:**
byte[] - Tableau d'octets
### getImage() {#getImage--}
```
public final IImage getImage()
```


Renvoie une copie d'une image. Lecture seule [IImage](../../com.aspose.slides/iimage).

**Returns:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```


Renvoie ou définit l'objet ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Cette valeur indique que cette image a été créée à partir de SVG.

**Returns:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```


Renvoie ou définit l'objet ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

Cette valeur indique que cette image a été créée à partir de SVG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```


Remplace les données de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newImageData | byte[] | Les données de la nouvelle image. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```


Remplace les données de l'image. Attention : lorsque l'image est un métafichier - elle sera rasterisée. Utilisez ReplaceImage(byte[]) à la place

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | La nouvelle image. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```


Remplace les données de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | Le nouveau IPPImage. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```


Renvoie un type MIME d'une image, encodé dans  BinaryData (\#getBinaryData.getBinaryData). Lecture seule String.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Renvoie la largeur d'une image. Lecture seule  int .

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Renvoie la hauteur d'une image. Lecture seule  int .

**Returns:**
int
### getX() {#getX--}
```
public final int getX()
```


Renvoie le décalage X d'une image. Lecture seule  int .

**Returns:**
int
### getY() {#getY--}
```
public final int getY()
```


Renvoie le décalage Y d'une image. Lecture seule  int .

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage d'une image.

**Returns:**
int - Hash code.
### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'objet.
---
title: IImageCollection
second_title: Référence API Java d'Aspose.Slides pour Android
description: Représente une collection de PPImage.
type: docs
url: /fr/com.aspose.slides/iimagecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

Représente une collection de PPImage.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'image par son index. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | Ajoute une image à une présentation. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | Ajoute une image à une présentation depuis un flux. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | Crée et ajoute une image à une présentation depuis un flux. |
| [addImage(byte[] buffer)](#addImage-byte---) | Ajoute une image à une présentation à partir du tampon spécifié. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | Ajoute une copie d'une image d'une autre présentation. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | Ajoute une image à une présentation depuis un objet SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


Renvoie l'image par son index.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index. |

**Valeur de retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


Ajoute une image à une présentation.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | Image à ajouter.

--------------------

Cette méthode convertit les métafichiers WMF/EMF en image PNG raster avant de les insérer dans une présentation. |

**Valeur de retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


Ajoute une image à une présentation depuis un flux.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux à partir duquel ajouter l'image.

--------------------

Cette méthode peut ajouter des métafichiers WMF/EMF à une présentation sans les convertir en image PNG raster. |

**Valeur de retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


Crée et ajoute une image à une présentation depuis un flux.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux à partir duquel ajouter le fichier image. |
| loadingStreamBehavior | int | Le comportement qui sera appliqué au flux. |

**Valeur de retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Ajoutée [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


Ajoute une image à une présentation à partir du tampon spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | byte[] | Tampon. |

**Valeur de retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


Ajoute une copie d'une image d'une autre présentation.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | Image source. |

**Valeur de retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


Ajoute une image à une présentation depuis un objet SVG.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Objet image SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**Valeur de retour:**
[IPPImage](../../com.aspose.slides/ippimage) - Image ajoutée.
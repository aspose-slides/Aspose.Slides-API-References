---
title: ISlidesPicture
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une image dans une présentation.
type: docs
url: /fr/com.aspose.slides/islidespicture/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)  
```
public interface ISlidesPicture extends ISlideComponent
```

Représente une image dans une présentation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getImage()](#getImage--) | Renvoie ou définit l'image intégrée. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Renvoie ou définit l'image intégrée. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie ou définit l'URL de l'image liée. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie ou définit l'URL de l'image liée. |
| [getImageTransform()](#getImageTransform--) | Renvoie la collection des effets de transformation d'image. |

### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```

Renvoie ou définit l'image intégrée. Lecture/écriture [IPPImage](../../com.aspose.slides/ippimage).

**Renvoie :**  
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```

Renvoie ou définit l'image intégrée. Lecture/écriture [IPPImage](../../com.aspose.slides/ippimage).

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Renvoie ou définit l'URL de l'image liée. Lecture/écriture String.

**Renvoie :**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Renvoie ou définit l'URL de l'image liée. Lecture/écriture String.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```

Renvoie la collection des effets de transformation d'image. Lecture seule [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Renvoie :**  
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
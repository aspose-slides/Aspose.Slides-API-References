---
title: Picture
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente une image dans une présentation.
type: docs
url: /fr/com.aspose.slides/picture/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)
```
public final class Picture implements IPVIObject, ISlidesPicture
```

Représente une image dans une présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | Renvoie ou définit l'image intégrée. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | Renvoie ou définit l'image intégrée. |
| [getLinkPathLong()](#getLinkPathLong--) | Renvoie ou définit l'URL de l'image liée. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Renvoie ou définit l'URL de l'image liée. |
| [getImageTransform()](#getImageTransform--) | Renvoie la collection des effets de transformation d'image. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Compare avec l'objet spécifié. |
| [hashCode()](#hashCode--) | Renvoie le hachage. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d'une image. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Lecture seule long.

**Renvoie :**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Renvoie le parent IPresentationComponent. Lecture seule [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Renvoie :**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getImage() {#getImage--}
```
public final IPPImage getImage()
```


Renvoie ou définit l'image intégrée. Lecture/écriture [IPPImage](../../com.aspose.slides/ippimage).

**Renvoie :**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```


Renvoie ou définit l'image intégrée. Lecture/écriture [IPPImage](../../com.aspose.slides/ippimage).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```


Renvoie ou définit l'URL de l'image liée. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```


Renvoie ou définit l'URL de l'image liée. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```


Renvoie la collection des effets de transformation d'image. Lecture seule [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**Renvoie :**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Renvoie la présentation. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Compare avec l'objet spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Objet à comparer. |

**Renvoie :**
boolean - Vrai si les objets sont égaux, sinon faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le hachage.

**Renvoie :**
int - Hachage.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Renvoie la diapositive parente d'une image. Lecture seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
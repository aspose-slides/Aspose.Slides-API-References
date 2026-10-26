---
title: IPictureFrame
second_title: Référence de l'API Java via Aspose.Slides pour Android
description: Représente un cadre contenant une image.
type: docs
url: /fr/com.aspose.slides/ipictureframe/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

Représente un cadre contenant une image.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | Renvoie les verrous de PictureFrame. |
| [getPictureFormat()](#getPictureFormat--) | Renvoie l'objet PictureFillFormat pour un cadre d'image. |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | Renvoie ou définit l'échelle de la hauteur (par rapport à la taille originale de l'image) du cadre d'image. |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | Renvoie ou définit l'échelle de la hauteur (par rapport à la taille originale de l'image) du cadre d'image. |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | Renvoie ou définit l'échelle de la largeur (par rapport à la taille originale de l'image) du cadre d'image. |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | Renvoie ou définit l'échelle de la largeur (par rapport à la taille originale de l'image) du cadre d'image. |

### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

Renvoie les verrous de PictureFrame. Lecture seule [IPictureFrameLock](../../com.aspose.slides/ipictureframelock).

**Renvoie :**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)

### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

Renvoie l'objet PictureFillFormat pour un cadre d'image. Lecture seule [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Renvoie :**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

Renvoie ou définit l'échelle de la hauteur (par rapport à la taille originale de l'image) du cadre d'image. La valeur 1.0 correspond à 100 %. Lecture/écriture float.

**Renvoie :**
float

### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

Renvoie ou définit l'échelle de la hauteur (par rapport à la taille originale de l'image) du cadre d'image. La valeur 1.0 correspond à 100 %. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

Renvoie ou définit l'échelle de la largeur (par rapport à la taille originale de l'image) du cadre d'image. La valeur 1.0 correspond à 100 %. Lecture/écriture float.

**Renvoie :**
float

### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

Renvoie ou définit l'échelle de la largeur (par rapport à la taille originale de l'image) du cadre d'image. La valeur 1.0 correspond à 100 %. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
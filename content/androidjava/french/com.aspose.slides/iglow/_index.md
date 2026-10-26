---
title: IGlow
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un effet de lueur dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet.
type: docs
url: /fr/com.aspose.slides/iglow/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Représente un effet de lueur, dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Rayon. |
| [setRadius(double value)](#setRadius-double-) | Rayon. |
| [getColor()](#getColor--) | Format de couleur. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Rayon. Lecture/écriture double.

**Retour:**  
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Rayon. Lecture/écriture double.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Format de couleur. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
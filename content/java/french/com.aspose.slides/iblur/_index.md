---
title: IBlur
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet de flou qui est appliqué à l'ensemble de la forme, y compris son remplissage.
type: docs
url: /fr/com.aspose.slides/iblur/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Représente un effet de flou appliqué à l'ensemble de la forme, y compris son remplissage. Tous les canaux de couleur, y compris l'alpha, sont affectés.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Returns or sets blur radius. |
| [setRadius(double value)](#setRadius-double-) | Returns or sets blur radius. |
| [getGrow()](#getGrow--) | Determines whether the bounds of the object should be grown as a result of the blurring. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determines whether the bounds of the object should be grown as a result of the blurring. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Renvoie ou définit le rayon du flou. Lecture/écriture double.

**Renvoie :**  
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Renvoie ou définit le rayon du flou. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Détermine si les limites de l'objet doivent être agrandies à la suite du flou. True indique que les limites sont agrandies tandis que false indique qu'elles ne le sont pas. Lecture/écriture boolean.

**Renvoie :**  
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Détermine si les limites de l'objet doivent être agrandies à la suite du flou. True indique que les limites sont agrandies tandis que false indique qu'elles ne le sont pas. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
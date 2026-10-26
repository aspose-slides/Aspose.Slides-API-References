---
title: IBlur
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente un effet de flou appliqué à toute la forme, y compris son remplissage.
type: docs
url: /fr/com.aspose.slides/iblur/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Représente un effet de flou appliqué à toute la forme, y compris son remplissage. Tous les canaux de couleur, y compris l'alpha, sont affectés.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Renvoie ou définit le rayon du flou. |
| [setRadius(double value)](#setRadius-double-) | Renvoie ou définit le rayon du flou. |
| [getGrow()](#getGrow--) | Détermine si les limites de l'objet doivent être agrandies à la suite du flou. |
| [setGrow(boolean value)](#setGrow-boolean-) | Détermine si les limites de l'objet doivent être agrandies à la suite du flou. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Renvoie ou définit le rayon du flou. Lecture/écriture double.

**Retour :**
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


Détermine si les limites de l'objet doivent être agrandies à la suite du flou. true indique que les limites sont agrandies tandis que false indique le contraire. Lecture/écriture booléen.

**Retour :**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Détermine si les limites de l'objet doivent être agrandies à la suite du flou. true indique que les limites sont agrandies tandis que false indique le contraire. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
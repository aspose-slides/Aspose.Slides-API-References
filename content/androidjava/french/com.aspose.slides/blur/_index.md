---
title: Blur
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un effet Blur qui est appliqué à l'ensemble de la forme, y compris son remplissage.
type: docs
url: /fr/com.aspose.slides/blur/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Représente un effet Blur qui est appliqué à toute la forme, y compris son remplissage. Tous les canaux de couleur, y compris alpha, sont affectés.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Renvoie ou définit le rayon du flou. |
| [setRadius(double value)](#setRadius-double-) | Renvoie ou définit le rayon du flou. |
| [getGrow()](#getGrow--) | Détermine si les limites de l'objet doivent être agrandies en raison du flou. |
| [setGrow(boolean value)](#setGrow-boolean-) | Détermine si les limites de l'objet doivent être agrandies en raison du flou. |
| [getEffective()](#getEffective--) | Obtient les données effectives de l'effet Blur avec l'héritage appliqué. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [Blur](../../com.aspose.slides/blur) spécifié est égal au [Blur](../../com.aspose.slides/blur) actuel. |
| [hashCode()](#hashCode--) | Sert de fonction de hachage pour un type particulier. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

Renvoie ou définit le rayon du flou. Lecture/écriture double.

**Renvoie :**
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Renvoie ou définit le rayon du flou. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Détermine si les limites de l'objet doivent être agrandies en raison du flou. True indique que les limites sont agrandies tandis que false indique qu'elles ne le sont pas. Lecture/écriture booléen.

**Renvoie :**
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Détermine si les limites de l'objet doivent être agrandies en raison du flou. True indique que les limites sont agrandies tandis que false indique qu'elles ne le sont pas. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Obtient les données effectives de l'effet Blur avec l'héritage appliqué.

**Renvoie :**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Un [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [Blur](../../com.aspose.slides/blur) spécifié est égal au [Blur](../../com.aspose.slides/blur) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'[Blur](../../com.aspose.slides/blur) à comparer. |

**Renvoie :**
boolean - true si les objets sont égaux ; sinon, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sert de fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l'objet actuel.
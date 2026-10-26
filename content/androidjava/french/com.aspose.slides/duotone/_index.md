---
title: Duotone
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente un effet Duotone.
type: docs
url: /fr/com.aspose.slides/duotone/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Représente un effet Duotone. Pour chaque pixel, combine Color1 et Color2 à l'aide d'une interpolation linéaire pour déterminer la nouvelle couleur de ce pixel.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor1()](#getColor1--) | Renvoie le format de couleur cible pour les pixels sombres. |
| [getColor2()](#getColor2--) | Renvoie le format de couleur cible pour les pixels clairs. |
| [getEffective()](#getEffective--) | Obtient les données effectives de l'effet Duotone avec l'héritage appliqué. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [Duotone](../../com.aspose.slides/duotone) spécifié est égal au [Duotone](../../com.aspose.slides/duotone) actuel. |
| [hashCode()](#hashCode--) | Servit de fonction de hachage pour un type particulier. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Renvoie le format de couleur cible pour les pixels sombres. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Renvoie le format de couleur cible pour les pixels clairs. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Obtient les données effectives de l'effet Duotone avec l'héritage appliqué.

**Renvoie :**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Lecture seule long.

**Renvoie :**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si le [Duotone](../../com.aspose.slides/duotone) spécifié est égal au [Duotone](../../com.aspose.slides/duotone) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [Duotone](../../com.aspose.slides/duotone) à comparer. |

**Renvoie :**
boolean - vrai si les objets sont égaux ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Servit de fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l'objet actuel.
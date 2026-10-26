---
title: ColorChange
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Représente un effet de changement de couleur.
type: docs
url: /fr/com.aspose.slides/colorchange/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Représente un effet Color Change. Les instances de FromColor sont remplacées par des instances de ToColor.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color qui sera remplacé. |
| [getToColor()](#getToColor--) | Color qui remplacera. |
| [getEffective()](#getEffective--) | Obtient les données effectives de l'effet Color Change avec l'héritage appliqué. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [ColorChange](../../com.aspose.slides/colorchange) spécifié est égal au [ColorChange](../../com.aspose.slides/colorchange) actuel. |
| [hashCode()](#hashCode--) | Servir de fonction de hachage pour un type particulier. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Color qui sera remplacé. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Color qui remplacera. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourne :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Obtient les données effectives de l'effet Color Change avec l'héritage appliqué.

**Retourne :**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Retourne :**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [ColorChange](../../com.aspose.slides/colorchange) spécifié est égal au [ColorChange](../../com.aspose.slides/colorchange) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [ColorChange](../../com.aspose.slides/colorchange) à comparer. |

**Retourne :**
boolean - vrai si les objets sont égaux ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Servir de fonction de hachage pour un type particulier.

**Retourne :**
int - Un code de hachage pour l'objet actuel.
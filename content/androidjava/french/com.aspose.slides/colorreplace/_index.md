---
title: ColorReplace
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente un effet de remplacement de couleur.
type: docs
url: /fr/com.aspose.slides/colorreplace/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Représente un effet de remplacement de couleur. Toutes les couleurs d'effet sont changées en une couleur fixe. Les valeurs alpha ne sont pas affectées.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColor()](#getColor--) | Renvoie le format de couleur qui remplacera la couleur de chaque pixel. |
| [getEffective()](#getEffective--) | Obtient les données effectives de l'effet de remplacement de couleur avec l'héritage appliqué. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [ColorReplace](../../com.aspose.slides/colorreplace) spécifié est égal au [ColorReplace](../../com.aspose.slides/colorreplace) actuel. |
| [hashCode()](#hashCode--) | Fournit une fonction de hachage pour un type particulier. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Renvoie le format de couleur qui remplacera la couleur de chaque pixel. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Obtient les données effectives de l'effet de remplacement de couleur avec l'héritage appliqué.

**Renvoie :**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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

Détermine si le [ColorReplace](../../com.aspose.slides/colorreplace) spécifié est égal au [ColorReplace](../../com.aspose.slides/colorreplace) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [ColorReplace](../../com.aspose.slides/colorreplace) à comparer. |

**Renvoie :**
boolean - vrai si les objets sont égaux ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fournit une fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l'objet actuel.
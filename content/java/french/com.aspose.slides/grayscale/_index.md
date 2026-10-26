---
title: GrayScale
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet en niveaux de gris.
type: docs
url: /fr/com.aspose.slides/grayscale/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Représente un effet en niveaux de gris. Convertit toutes les valeurs de couleur de l'effet en une nuance de gris, correspondant à leur luminance. Les valeurs alpha (opacité) de l'effet ne sont pas affectées.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Obtient les données de l'effet en niveaux de gris effectives avec l'héritage appliqué. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [GrayScale](../../com.aspose.slides/grayscale) spécifié est égal au [GrayScale](../../com.aspose.slides/grayscale) actuel. |
| [hashCode()](#hashCode--) | Servit de fonction de hachage pour un type particulier. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Obtient les données de l'effet en niveaux de gris effectives avec l'héritage appliqué.

**Retour :**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - Un [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [GrayScale](../../com.aspose.slides/grayscale) spécifié est égal au [GrayScale](../../com.aspose.slides/grayscale) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [GrayScale](../../com.aspose.slides/grayscale) à comparer. |

**Retour :**
boolean - true si les objets sont égaux ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Servit de fonction de hachage pour un type particulier.

**Retour :**
int - Un code de hachage pour l'objet actuel.
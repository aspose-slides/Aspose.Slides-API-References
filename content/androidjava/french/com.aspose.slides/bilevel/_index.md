---
title: BiLevel
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un effet bi-niveau noir/blanc.
type: docs
url: /fr/com.aspose.slides/bilevel/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Représente un effet bi-niveau (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur seuil spécifiée sont changées en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont définies en blanc. Les valeurs d'effet alpha ne sont pas affectées par cet effet.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Obtient les données d'effet bi-niveau effectif avec l'héritage appliqué. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [BiLevel](../../com.aspose.slides/bilevel) spécifié est égal au [BiLevel](../../com.aspose.slides/bilevel) actuel. |
| [hashCode()](#hashCode--) | Sert de fonction de hachage pour un type particulier. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Obtient les données d'effet bi-niveau effectif avec l'héritage appliqué.

**Retourne :**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Un [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [BiLevel](../../com.aspose.slides/bilevel) spécifié est égal au [BiLevel](../../com.aspose.slides/bilevel) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [BiLevel](../../com.aspose.slides/bilevel) à comparer. |

**Retourne :**
boolean - true si les objets sont égaux ; sinon, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sert de fonction de hachage pour un type particulier.

**Retourne :**
int - Un code de hachage pour l'objet actuel.
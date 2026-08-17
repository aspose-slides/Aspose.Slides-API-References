---
title: BiLevel
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet bi-niveau noir/blanc.
type: docs
url: /fr/com.aspose.slides/bilevel/
---
**Héritage**:
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées**:
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Représente un effet bi-niveau (noir/blanc). Les couleurs d'entrée dont la luminance est inférieure à la valeur seuil spécifiée sont converties en noir. Les couleurs d'entrée dont la luminance est supérieure ou égale à la valeur spécifiée sont réglées sur blanc. Les valeurs d'effet alpha ne sont pas affectées par cet effet.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Obtient les données d'effet bi-niveau effectives avec l'héritage appliqué. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [BiLevel](../../com.aspose.slides/bilevel) spécifié est égal au [BiLevel](../../com.aspose.slides/bilevel) actuel. |
| [hashCode()](#hashCode--) | Servir de fonction de hachage pour un type particulier. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Obtient les données d'effet bi-niveau effectives avec l'héritage appliqué.

**Renvoie :**
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

**Renvoie :**
boolean - vrai si les objets sont égaux ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Servir de fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l'objet actuel.
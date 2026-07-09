---
title: AlphaBiLevel
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente un effet Alpha Bi-Level.
type: docs
url: /fr/com.aspose.slides/alphabilevel/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Représente un effet Alpha Bi-Level. Les valeurs Alpha (Opacity) inférieures au seuil sont modifiées à 0 (complètement transparent) et les valeurs alpha supérieures ou égales au seuil sont modifiées à 100 % (complètement opaque).

## Méthodes

| Méthode | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returns effect threshold. |
| [setThreshold(float value)](#setThreshold-float-) | Returns effect threshold. |
| [getEffective()](#getEffective--) | Gets effective Alpha Bi-Level effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaBiLevel](../../com.aspose.slides/alphabilevel) is equal to the current [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Renvoie le seuil de l'effet. Lecture/écriture float.

**Renvoie :**
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Renvoie le seuil de l'effet. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Obtient les données effectives de l'effet Alpha Bi-Level avec l'héritage appliqué.

**Renvoie :**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - Un [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [AlphaBiLevel](../../com.aspose.slides/alphabilevel) spécifié est égal au [AlphaBiLevel](../../com.aspose.slides/alphabilevel) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [AlphaBiLevel](../../com.aspose.slides/alphabilevel) à comparer. |

**Renvoie :**
boolean - true si les objets sont égaux ; sinon, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Servir de fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l'objet actuel.
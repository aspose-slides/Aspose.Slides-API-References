---
title: AlphaBiLevel
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet Alpha à deux niveaux.
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

Représente un effet Alpha à deux niveaux. Les valeurs Alpha (opacité) inférieures au seuil sont changées à 0 (totalement transparent) et les valeurs alpha supérieures ou égales au seuil sont changées à 100 % (totalement opaque).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Renvoie le seuil de l'effet. |
| [setThreshold(float value)](#setThreshold-float-) | Renvoie le seuil de l'effet. |
| [getEffective()](#getEffective--) | Obtient les données d'effet Alpha à deux niveaux effectif avec l'héritage appliqué. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [AlphaBiLevel](../../com.aspose.slides/alphabilevel) spécifié est égal au [AlphaBiLevel](../../com.aspose.slides/alphabilevel) actuel. |
| [hashCode()](#hashCode--) | Servir de fonction de hachage pour un type particulier. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Renvoie le seuil de l'effet. Lecture/écriture float.

**Retour :**
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


Obtient les données d'effet Alpha à deux niveaux effectif avec l'héritage appliqué.

**Retour :**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si le [AlphaBiLevel](../../com.aspose.slides/alphabilevel) spécifié est égal au [AlphaBiLevel](../../com.aspose.slides/alphabilevel) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [AlphaBiLevel](../../com.aspose.slides/alphabilevel) à comparer. |

**Retour :**
boolean - vrai si les objets sont égaux ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Servir de fonction de hachage pour un type particulier.

**Retour :**
int - Un code de hachage pour l'objet actuel.
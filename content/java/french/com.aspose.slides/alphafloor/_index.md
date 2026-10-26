---
title: AlphaFloor
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet Alpha Floor.
type: docs
url: /fr/com.aspose.slides/alphafloor/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100 % sont remplacées par zéro. En d'autres termes, tout ce qui est partiellement transparent devient entièrement transparent.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Obtient les données d'effet Alpha Floor effectives avec l'héritage appliqué. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [AlphaFloor](../../com.aspose.slides/alphafloor) spécifié est égal au [AlphaFloor](../../com.aspose.slides/alphafloor) actuel. |
| [hashCode()](#hashCode--) | Fonctionne comme une fonction de hachage pour un type particulier. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

Obtient les données d'effet Alpha Floor effectives avec l'héritage appliqué.

**Renvoie :**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Un [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [AlphaFloor](../../com.aspose.slides/alphafloor) spécifié est égal au [AlphaFloor](../../com.aspose.slides/alphafloor) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [AlphaFloor](../../com.aspose.slides/alphafloor) à comparer. |

**Renvoie :**
boolean - true si les objets sont égaux ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fonctionne comme une fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l'objet actuel.
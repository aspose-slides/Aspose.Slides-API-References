---
title: AlphaFloor
second_title: Aspose.Slides pour Android via la référence d'API Java
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

Représente un effet Alpha Floor. Les valeurs Alpha (opacité) inférieures à 100% sont converties en zéro. En d'autres termes, tout ce qui est partiellement transparent devient entièrement transparent.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Floor effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Obtient les données effectives de l'effet Alpha Floor avec l'héritage appliqué.

**Renvoie :**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
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
boolean - vrai si les objets sont égaux ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fournit une fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l'objet actuel.
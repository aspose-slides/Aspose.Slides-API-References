---
title: AlphaModulate
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente un effet Alpha Modulate.
type: docs
url: /fr/com.aspose.slides/alphamodulate/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

Représente un effet Alpha Modulate. Les valeurs d’alpha (opacité) de l’effet sont multipliées par un pourcentage fixe. Le conteneur d’effet indique un effet contenant des valeurs d’alpha à moduler.
## Méthodes

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Modulate effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaModulate](../../com.aspose.slides/alphamodulate) is equal to the current [AlphaModulate](../../com.aspose.slides/alphamodulate). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```

Obtient les données d’effet Alpha Modulate effectives avec l’héritage appliqué.

**Renvoie :**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - Un [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [AlphaModulate](../../com.aspose.slides/alphamodulate) spécifié est égal à l[AlphaModulate](../../com.aspose.slides/alphamodulate) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [AlphaModulate](../../com.aspose.slides/alphamodulate) à comparer. |

**Renvoie :**
boolean - true si les objets sont égaux ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Servit de fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l’objet actuel.
---
title: ColorChange
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet de changement de couleur.
type: docs
url: /fr/com.aspose.slides/colorchange/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect  
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Représente un effet de changement de couleur. Les instances de FromColor sont remplacées par des instances de ToColor.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Couleur qui sera remplacée. |
| [getToColor()](#getToColor--) | Couleur qui remplacera. |
| [getEffective()](#getEffective--) | Obtient les données effectives de l'effet de changement de couleur avec l'héritage appliqué. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [ColorChange](../../com.aspose.slides/colorchange) spécifié est égal au [ColorChange](../../com.aspose.slides/colorchange) actuel. |
| [hashCode()](#hashCode--) | Sert de fonction de hachage pour un type particulier. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Couleur qui sera remplacée. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Couleur qui remplacera. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Obtient les données effectives de l'effet de changement de couleur avec l'héritage appliqué.

**Retour:**  
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Un [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Retour:**  
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [ColorChange](../../com.aspose.slides/colorchange) spécifié est égal au [ColorChange](../../com.aspose.slides/colorchange) actuel.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [ColorChange](../../com.aspose.slides/colorchange) à comparer. |

**Retour:**  
boolean - true si les objets sont égaux ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sert de fonction de hachage pour un type particulier.

**Retour:**  
int - Un code de hachage pour l'objet actuel.
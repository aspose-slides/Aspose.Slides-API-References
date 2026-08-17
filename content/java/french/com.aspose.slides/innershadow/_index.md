---
title: InnerShadow
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un effet d'ombre interne.
type: docs
url: /fr/com.aspose.slides/innershadow/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IInnerShadow](../../com.aspose.slides/iinnershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class InnerShadow implements IInnerShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Représente un effet d'ombre interne.  
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Rayon du flou. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Rayon du flou. |
| [getDirection()](#getDirection--) | Direction de l'ombre. |
| [setDirection(float value)](#setDirection-float-) | Direction de l'ombre. |
| [getDistance()](#getDistance--) | Distance de l'ombre. |
| [setDistance(double value)](#setDistance-double-) | Distance de l'ombre. |
| [getShadowColor()](#getShadowColor--) | Couleur de l'ombre. |
| [getEffective()](#getEffective--) | Obtient les données d'effet d'ombre interne effectives avec l'héritage appliqué. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [InnerShadow](../../com.aspose.slides/innershadow) spécifié est égal au [InnerShadow](../../com.aspose.slides/innershadow) actuel. |
| [hashCode()](#hashCode--) | Fonctionne comme fonction de hachage pour un type particulier. |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```

Rayon du flou. Lecture/écriture double.

**Retour :**  
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```

Rayon du flou. Lecture/écriture double.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Direction de l'ombre. Lecture/écriture float.

**Retour :**  
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Direction de l'ombre. Lecture/écriture float.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Distance de l'ombre. Lecture/écriture double.

**Retour :**  
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Distance de l'ombre. Lecture/écriture double.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Couleur de l'ombre. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour :**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IInnerShadowEffectiveData getEffective()
```

Obtient les données d'effet d'ombre interne effectives avec l'héritage appliqué.

**Retour :**  
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata) - Un [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Retour :**  
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Lecture seule long.

**Retour :**  
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Renvoie le IPresentationComponent parent. Lecture seule [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Retour :**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [InnerShadow](../../com.aspose.slides/innershadow) spécifié est égal au [InnerShadow](../../com.aspose.slides/innershadow) actuel.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [InnerShadow](../../com.aspose.slides/innershadow) à comparer. |

**Retour :**  
boolean - vrai si les objets sont égaux ; sinon, faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fonctionne comme fonction de hachage pour un type particulier.

**Retour :**  
int - Un code de hachage pour l'objet actuel.
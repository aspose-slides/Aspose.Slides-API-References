---
title: SoftEdge
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un effet de bord doux.
type: docs
url: /fr/com.aspose.slides/softedge/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Représente un effet de bord souple. Les bords de la forme sont floutés, tandis que le remplissage n’est pas affecté.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Spécifie le rayon du flou à appliquer aux bords. |
| [setRadius(double value)](#setRadius-double-) | Spécifie le rayon du flou à appliquer aux bords. |
| [getEffective()](#getEffective--) | Obtient les données effectives de l’effet Soft Edge avec l’héritage appliqué. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [SoftEdge](../../com.aspose.slides/softedge) spécifié est égal au [SoftEdge](../../com.aspose.slides/softedge) actuel. |
| [hashCode()](#hashCode--) | Sert de fonction de hachage pour un type particulier. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Spécifie le rayon du flou à appliquer aux bords. Lecture/écriture double.

**Renvoie :**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Spécifie le rayon du flou à appliquer aux bords. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Obtient les données effectives de l’effet Soft Edge avec l’héritage appliqué.

**Renvoie :**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - Un [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Renvoie le parent IPresentationComponent. Lecture seule [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Renvoie :**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si le [SoftEdge](../../com.aspose.slides/softedge) spécifié est égal au [SoftEdge](../../com.aspose.slides/softedge) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [SoftEdge](../../com.aspose.slides/softedge) à comparer. |

**Renvoie :**
boolean - true si les objets sont égaux ; sinon false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Sert de fonction de hachage pour un type particulier.

**Renvoie :**
int - Un code de hachage pour l’objet actuel.
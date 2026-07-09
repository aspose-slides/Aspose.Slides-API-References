---
title: Glow
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un effet Glow dans lequel un contour flou de couleur est ajouté à l'extérieur des bords de l'objet.
type: docs
url: /fr/com.aspose.slides/glow/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable  
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Représente un effet Glow, dans lequel un contour flou de couleur est ajouté à l’extérieur des bords de l’objet.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Rayon. |
| [setRadius(double value)](#setRadius-double-) | Rayon. |
| [getColor()](#getColor--) | Format de couleur. |
| [getEffective()](#getEffective--) | Obtient les données effectives de l’effet Glow avec l’héritage appliqué. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [Glow](../../com.aspose.slides/glow) spécifié est égal au [Glow](../../com.aspose.slides/glow) actuel. |
| [hashCode()](#hashCode--) | Sert de fonction de hachage pour un type particulier. |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

Rayon. Lecture/écriture double.

**Renvoie :**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Rayon. Lecture/écriture double.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Format de couleur. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

Obtient les données effectives de l’effet Glow avec l’héritage appliqué.

**Renvoie :**  
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - Un [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

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

Détermine si le [Glow](../../com.aspose.slides/glow) spécifié est égal au [Glow](../../com.aspose.slides/glow) actuel.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [Glow](../../com.aspose.slides/glow) à comparer. |

**Renvoie :**  
boolean - true si les objets sont égaux ; sinon, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Sert de fonction de hachage pour un type particulier.

**Renvoie :**  
int - Un code de hachage pour l’objet actuel.
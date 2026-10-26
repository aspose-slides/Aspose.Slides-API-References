---
title: PresetShadow
second_title: Référence API Java Aspose.Slides pour Android
description: Représente un effet d'ombre prédéfini.
type: docs
url: /fr/com.aspose.slides/presetshadow/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Représente un effet Preset Shadow.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Direction de l'ombre. |
| [setDirection(float value)](#setDirection-float-) | Direction de l'ombre. |
| [getDistance()](#getDistance--) | Distance de l'ombre. |
| [setDistance(double value)](#setDistance-double-) | Distance de l'ombre. |
| [getShadowColor()](#getShadowColor--) | Couleur de l'ombre. |
| [getPreset()](#getPreset--) | Préréglage. |
| [setPreset(int value)](#setPreset-int-) | Préréglage. |
| [getEffective()](#getEffective--) | Obtient les données effectives de l'effet Preset Shadow avec l'héritage appliqué. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [PresetShadow](../../com.aspose.slides/presetshadow) spécifié est égal au [PresetShadow](../../com.aspose.slides/presetshadow) actuel. |
| [hashCode()](#hashCode--) | Servit de fonction de hachage pour un type particulier. |

### getDirection() {#getDirection--}
```
public final float getDirection()
```

Direction de l'ombre. Lecture/écriture  float .

**Renvoie :**
float

### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Direction de l'ombre. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public final double getDistance()
```

Distance de l'ombre. Lecture/écriture  double .

**Renvoie :**
double

### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Distance de l'ombre. Lecture/écriture  double .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Couleur de l'ombre. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPreset() {#getPreset--}
```
public final int getPreset()
```

Préréglage. Lecture/écriture [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Renvoie :**
int

### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Préréglage. Lecture/écriture [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Obtient les données effectives de l'effet Preset Shadow avec l'héritage appliqué.

**Renvoie :**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - A [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

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

Détermine si le [PresetShadow](../../com.aspose.slides/presetshadow) spécifié est égal au [PresetShadow](../../com.aspose.slides/presetshadow) actuel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le [PresetShadow](../../com.aspose.slides/presetshadow) à comparer. |

**Renvoie :**
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Servit de fonction de hachage pour un type particulier.

**Renvoie :**
int - A hash code for the current object.
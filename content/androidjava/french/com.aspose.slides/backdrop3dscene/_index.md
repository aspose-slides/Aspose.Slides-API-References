---
title: Backdrop3DScene
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Définit un plan dans lequel les effets tels que la lueur et l'ombre sont appliqués par rapport à la forme à laquelle ils sont appliqués.
type: docs
url: /fr/com.aspose.slides/backdrop3dscene/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Définit un plan dans lequel les effets, tels que la lueur et l'ombre, sont appliqués par rapport à la forme à laquelle ils sont appliqués.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Renvoie ou définit un vecteur normal. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Renvoie ou définit un vecteur normal. |
| [getAnchorPoint()](#getAnchorPoint--) | Renvoie ou définit un point dans l'espace 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Renvoie ou définit un point dans l'espace 3D. |
| [getUpVector()](#getUpVector--) | Renvoie ou définit un vecteur représentant le haut. |
| [setUpVector(float[] value)](#setUpVector-float---) | Renvoie ou définit un vecteur représentant le haut. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Renvoie ou définit un vecteur normal. Pour être plus précis, cet attribut définit un vecteur normal à la face du plan d'arrière-plan. Vecteur représenté par un tableau de 3 valeurs float qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Renvoie :**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Renvoie ou définit un vecteur normal. Pour être plus précis, cet attribut définit un vecteur normal à la face du plan d'arrière-plan. Vecteur représenté par un tableau de 3 valeurs float qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Renvoie ou définit un point dans l'espace 3D. Ce point est le point dans l'espace qui ancre le plan d'arrière-plan. Point 3D représenté par un tableau de 3 valeurs float qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Renvoie :**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Renvoie ou définit un point dans l'espace 3D. Ce point est le point dans l'espace qui ancre le plan d'arrière-plan. Point 3D représenté par un tableau de 3 valeurs float qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Renvoie ou définit un vecteur représentant le haut. Pour être plus précis, cet attribut définit un vecteur représentant le haut par rapport à la face du plan d'arrière-plan. Vecteur représenté par un tableau de 3 valeurs float qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Renvoie :**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Renvoie ou définit un vecteur représentant le haut. Pour être plus précis, cet attribut définit un vecteur représentant le haut par rapport à la face du plan d'arrière-plan. Vecteur représenté par un tableau de 3 valeurs float qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |
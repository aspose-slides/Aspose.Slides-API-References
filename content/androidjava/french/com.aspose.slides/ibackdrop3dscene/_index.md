---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Définit un plan dans lequel des effets tels que la lueur et l'ombre sont appliqués par rapport à la forme à laquelle ils sont appliqués.
type: docs
url: /fr/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Définit un plan dans lequel des effets, tels que la lueur et l'ombre, sont appliqués par rapport à la forme à laquelle ils sont appliqués.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Retourne ou définit un vecteur normal. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Retourne ou définit un vecteur normal. |
| [getAnchorPoint()](#getAnchorPoint--) | Retourne ou définit un point dans l'espace 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Retourne ou définit un point dans l'espace 3D. |
| [getUpVector()](#getUpVector--) | Retourne ou définit un vecteur représentant le haut. |
| [setUpVector(float[] value)](#setUpVector-float---) | Retourne ou définit un vecteur représentant le haut. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Retourne ou définit un vecteur normal. Pour être plus précis, cet attribut définit un vecteur perpendiculaire à la face du plan de toile de fond. Vecteur représenté par un tableau de 3 valeurs flottantes qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Valeur retournée :**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Retourne ou définit un vecteur normal. Pour être plus précis, cet attribut définit un vecteur perpendiculaire à la face du plan de toile de fond. Vecteur représenté par un tableau de 3 valeurs flottantes qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Retourne ou définit un point dans l'espace 3D. Ce point ancre le plan de toile de fond. Point 3D représenté par un tableau de 3 valeurs flottantes qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Valeur retournée :**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Retourne ou définit un point dans l'espace 3D. Ce point ancre le plan de toile de fond. Point 3D représenté par un tableau de 3 valeurs flottantes qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Retourne ou définit un vecteur représentant le haut. Pour être plus précis, cet attribut définit un vecteur représentant le haut par rapport à la face du plan de toile de fond. Vecteur représenté par un tableau de 3 valeurs flottantes qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Valeur retournée :**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Retourne ou définit un vecteur représentant le haut. Pour être plus précis, cet attribut définit un vecteur représentant le haut par rapport à la face du plan de toile de fond. Vecteur représenté par un tableau de 3 valeurs flottantes qui définissent les coordonnées X, Y et Z. Lecture/écriture float[].

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float[] |  |
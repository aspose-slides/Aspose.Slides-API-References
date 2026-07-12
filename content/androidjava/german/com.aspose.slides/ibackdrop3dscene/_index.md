---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Definiert eine Ebene, in der Effekte wie Leuchten und Schatten in Bezug auf die Form angewendet werden, zu der sie gehören.
type: docs
url: /de/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Definiert eine Ebene, in der Effekte wie Leuchten und Schatten in Bezug auf die Form angewendet werden, zu der sie gehören.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Gibt einen Normalvektor zurück oder setzt ihn. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Gibt einen Normalvektor zurück oder setzt ihn. |
| [getAnchorPoint()](#getAnchorPoint--) | Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. |
| [getUpVector()](#getUpVector--) | Gibt einen nach oben zeigenden Vektor zurück oder setzt ihn. |
| [setUpVector(float[] value)](#setUpVector-float---) | Gibt einen nach oben zeigenden Vektor zurück oder setzt ihn. |

### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Gibt einen Normalvektor zurück oder setzt ihn. Präziser definiert dieses Attribut einen Vektor, der senkrecht zur Fläche der Hintergrundebene steht. Der Vektor wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten bestimmen. Lesen/Schreiben float[].

**Rückgabewert:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Gibt einen Normalvektor zurück oder setzt ihn. Präziser definiert dieses Attribut einen Vektor, der senkrecht zur Fläche der Hintergrundebene steht. Der Vektor wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten bestimmen. Lesen/Schreiben float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. Dieser Punkt ist der Ankerpunkt der Hintergrundebene im Raum. Der 3D-Punkt wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten bestimmen. Lesen/Schreiben float[].

**Rückgabewert:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. Dieser Punkt ist der Ankerpunkt der Hintergrundebene im Raum. Der 3D-Punkt wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten bestimmen. Lesen/Schreiben float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Gibt einen nach oben zeigenden Vektor zurück oder setzt ihn. Präziser definiert dieses Attribut einen Vektor, der in Bezug auf die Fläche der Hintergrundebene nach oben zeigt. Der Vektor wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten bestimmen. Lesen/Schreiben float[].

**Rückgabewert:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Gibt einen nach oben zeigenden Vektor zurück oder setzt ihn. Präziser definiert dieses Attribut einen Vektor, der in Bezug auf die Fläche der Hintergrundebene nach oben zeigt. Der Vektor wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten bestimmen. Lesen/Schreiben float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |
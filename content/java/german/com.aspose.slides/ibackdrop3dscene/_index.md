---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Definiert eine Ebene, in der Effekte wie Leuchten und Schatten in Bezug auf die Form angewendet werden, auf die sie angewendet werden.
type: docs
url: /de/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Definiert eine Ebene, in der Effekte, wie Leuchten und Schatten, in Bezug auf die Form angewendet werden, zu der sie gehören.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Gibt einen Normalvektor zurück oder setzt ihn. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Gibt einen Normalvektor zurück oder setzt ihn. |
| [getAnchorPoint()](#getAnchorPoint--) | Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. |
| [getUpVector()](#getUpVector--) | Gibt einen Vektor zurück, der nach oben zeigt, oder setzt ihn. |
| [setUpVector(float[] value)](#setUpVector-float---) | Gibt einen Vektor zurück, der nach oben zeigt, oder setzt ihn. |

### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Gibt einen Normalvektor zurück oder setzt ihn. Genauer gesagt definiert dieses Attribut einen Vektor, der senkrecht zur Fläche der Hintergrundebene steht. Der Vektor wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lesen/Schreiben float[].

**Rückgabe:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Gibt einen Normalvektor zurück oder setzt ihn. Genauer gesagt definiert dieses Attribut einen Vektor, der senkrecht zur Fläche der Hintergrundebene steht. Der Vektor wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lesen/Schreiben float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. Dieser Punkt ist der Ankerpunkt der Hintergrundebene. 3D-Punkt wird durch ein Array von 3 float-Werten dargestellt, die X-, Y- und Z-Koordinaten definieren. Lesen/Schreiben float[].

**Rückgabe:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. Dieser Punkt ist der Ankerpunkt der Hintergrundebene. 3D-Punkt wird durch ein Array von 3 float-Werten dargestellt, die X-, Y- und Z-Koordinaten definieren. Lesen/Schreiben float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Gibt einen Vektor zurück, der nach oben zeigt, oder setzt ihn. Genauer gesagt definiert dieses Attribut einen Vektor, der in Bezug auf die Fläche der Hintergrundebene nach oben zeigt. Der Vektor wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lesen/Schreiben float[].

**Rückgabe:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Gibt einen Vektor zurück, der nach oben zeigt, oder setzt ihn. Genauer gesagt definiert dieses Attribut einen Vektor, der in Bezug auf die Fläche der Hintergrundebene nach oben zeigt. Der Vektor wird durch ein Array von 3 float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lesen/Schreiben float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |
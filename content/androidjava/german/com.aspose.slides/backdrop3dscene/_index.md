---
title: Backdrop3DScene
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Definiert eine Ebene, in der Effekte wie Leuchten und Schatten in Bezug auf die Form angewendet werden, auf die sie angewendet werden.
type: docs
url: /de/com.aspose.slides/backdrop3dscene/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Definiert eine Ebene, in der Effekte wie Leuchten und Schatten in Bezug auf die Form angewendet werden, auf die sie angewendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Gibt einen Normalvektor zurück oder setzt ihn. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Gibt einen Normalvektor zurück oder setzt ihn. |
| [getAnchorPoint()](#getAnchorPoint--) | Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. |
| [getUpVector()](#getUpVector--) | Gibt einen Vektor zurück, der nach oben zeigt, oder setzt ihn. |
| [setUpVector(float[] value)](#setUpVector-float---) | Gibt einen Vektor zurück, der nach oben zeigt, oder setzt ihn. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbar long.

**Rückgabewert:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Gibt einen Normalvektor zurück oder setzt ihn. Genau genommen definiert dieses Attribut einen Vektor, der senkrecht zur Fläche der Hintergrundebene steht. Der Vektor wird als Array von 3 Float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lese/Schreib float[].

**Rückgabewert:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Gibt einen Normalvektor zurück oder setzt ihn. Genau genommen definiert dieses Attribut einen Vektor, der senkrecht zur Fläche der Hintergrundebene steht. Der Vektor wird als Array von 3 Float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lese/Schreib float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. Dieser Punkt ist der Punkt im Raum, der die Hintergrundebene verankert. Der 3D-Punkt wird als Array von 3 Float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lese/Schreib float[].

**Rückgabewert:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Gibt einen Punkt im 3D-Raum zurück oder setzt ihn. Dieser Punkt ist der Punkt im Raum, der die Hintergrundebene verankert. Der 3D-Punkt wird als Array von 3 Float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lese/Schreib float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Gibt einen Vektor zurück, der nach oben zeigt, oder setzt ihn. Genau genommen definiert dieses Attribut einen Vektor, der nach oben zeigt in Bezug auf die Fläche der Hintergrundebene. Der Vektor wird als Array von 3 Float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lese/Schreib float[].

**Rückgabewert:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Gibt einen Vektor zurück, der nach oben zeigt, oder setzt ihn. Genau genommen definiert dieses Attribut einen Vektor, der nach oben zeigt in Bezug auf die Fläche der Hintergrundebene. Der Vektor wird als Array von 3 Float-Werten dargestellt, die die X-, Y- und Z-Koordinaten definieren. Lese/Schreib float[].

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float[] |  |
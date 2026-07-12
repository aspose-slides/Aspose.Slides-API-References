---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /hu/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Meghatároz egy síkot, amelyben a hatások, például a ragyogás és az árnyék, a rájuk alkalmazott alakzathoz viszonyítva kerülnek alkalmazásra.
## Metódusok

| Method | Description |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Visszaad vagy beállít egy normál vektort. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Visszaad vagy beállít egy normál vektort. |
| [getAnchorPoint()](#getAnchorPoint--) | Visszaad vagy beállít egy pontot a 3D térben. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Visszaad vagy beállít egy pontot a 3D térben. |
| [getUpVector()](#getUpVector--) | Visszaad vagy beállít egy felfelé mutató vektort. |
| [setUpVector(float[] value)](#setUpVector-float---) | Visszaad vagy beállít egy felfelé mutató vektort. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Visszaad vagy beállít egy normál vektort. Pontosabban, ez a tulajdonság egy, a háttér sík felületére merőleges vektort határoz meg. A vektor 3 float értékből álló tömbként van reprezentálva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatér:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Visszaad vagy beállít egy normál vektort. Pontosabban, ez a tulajdonság egy, a háttér sík felületére merőleges vektort határoz meg. A vektor 3 float értékből álló tömbként van reprezentálva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Visszaad vagy beállít egy pontot a 3D térben. Ez a pont az a hely a térben, amely rögzíti a háttér síkot. A 3D pont 3 float értékből álló tömbként van reprezentálva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatér:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Visszaad vagy beállít egy pontot a 3D térben. Ez a pont az a hely a térben, amely rögzíti a háttér síkot. A 3D pont 3 float értékből álló tömbként van reprezentálva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Visszaad vagy beállít egy felfelé mutató vektort. Pontosabban, ez a tulajdonság egy, a háttér sík felületéhez viszonyítva felfelé mutató vektort határoz meg. A vektor 3 float értékből álló tömbként van reprezentálva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatér:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Visszaad vagy beállít egy felfelé mutató vektort. Pontosabban, ez a tulajdonság egy, a háttér sík felületéhez viszonyítva felfelé mutató vektort határoz meg. A vektor 3 float értékből álló tömbként van reprezentálva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |
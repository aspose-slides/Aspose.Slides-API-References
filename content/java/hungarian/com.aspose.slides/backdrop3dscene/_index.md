---
title: Backdrop3DScene
second_title: Aspose.Slides Java API-referencia
description: Meghatároz egy síkot, amelyben a ragyogás és az árnyék hatásai az alakzathoz viszonyítva kerülnek alkalmazásra.
type: docs
url: /hu/com.aspose.slides/backdrop3dscene/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Egy síkot definiál, amelyben a hatások, például a ragyogás és az árnyék, a rájuk alkalmazott alakzathoz viszonyítva kerülnek alkalmazásra.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Visszaad vagy beállít egy normál vektort. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Visszaad vagy beállít egy normál vektort. |
| [getAnchorPoint()](#getAnchorPoint--) | Visszaad vagy beállít egy pontot a 3D térben. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Visszaad vagy beállít egy pontot a 3D térben. |
| [getUpVector()](#getUpVector--) | Visszaad vagy beállít egy felfelé irányuló vektort. |
| [setUpVector(float[] value)](#setUpVector-float---) | Visszaad vagy beállít egy felfelé irányuló vektort. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Visszaad vagy beállít egy normál vektort. Pontosabban, ez a tulajdonság egy a háttérsík felületére merőleges vektort határoz meg. A vektor 3 float értékből álló tömb, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatér:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Visszaad vagy beállít egy normál vektort. Pontosabban, ez a tulajdonság egy a háttérsík felületére merőleges vektort határoz meg. A vektor 3 float értékből álló tömb, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Visszaad vagy beállít egy pontot a 3D térben. Ez a pont a háttérsíkot rögzíti. 3D pont 3 float értékből álló tömb, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatér:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Visszaad vagy beállít egy pontot a 3D térben. Ez a pont a háttérsíkot rögzíti. 3D pont 3 float értékből álló tömb, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Visszaad vagy beállít egy felfelé irányuló vektort. Pontosabban, ez a tulajdonság egy felfelé irányuló vektort határoz meg a háttérsík felületéhez képest. A vektor 3 float értékből álló tömb, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatér:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Visszaad vagy beállít egy felfelé irányuló vektort. Pontosabban, ez a tulajdonság egy felfelé irányuló vektort határoz meg a háttérsík felületéhez képest. A vektor 3 float értékből álló tömb, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |
---
title: Backdrop3DScene
second_title: Aspose.Slides Androidhoz Java API hivatkozás alapján
description: Meghatároz egy síkot, amelyben a ragyogás és az árnyék hatásai a formához viszonyítva kerülnek alkalmazásra.
type: docs
url: /hu/com.aspose.slides/backdrop3dscene/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Meghatároz egy síkot, amelyben a hatások, például a ragyogás és az árnyék, a formához viszonyítva kerülnek alkalmazásra.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Visszaad vagy beállít egy normál vektort. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Visszaad vagy beállít egy normál vektort. |
| [getAnchorPoint()](#getAnchorPoint--) | Visszaad vagy beállít egy pontot a 3D térben. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Visszaad vagy beállít egy pontot a 3D térben. |
| [getUpVector()](#getUpVector--) | Visszaad vagy beállít egy fel felé mutató vektort. |
| [setUpVector(float[] value)](#setUpVector-float---) | Visszaad vagy beállít egy fel felé mutató vektort. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Visszaad vagy beállít egy normál vektort. Pontosabban, ez az attribútum egy, a háttérsík felületére merőleges vektort definiál. A vektor 3 float értékből álló tömbként van ábrázolva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatérési érték:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Visszaad vagy beállít egy normál vektort. Pontosabban, ez az attribútum egy, a háttérsík felületére merőleges vektort definiál. A vektor 3 float értékből álló tömbként van ábrázolva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Visszaad vagy beállít egy pontot a 3D térben. Ez a pont az a pont, amely a háttérsíkot rögzíti a térben. A 3D pont 3 float értékből álló tömbként van ábrázolva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatérési érték:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Visszaad vagy beállít egy pontot a 3D térben. Ez a pont az a pont, amely a háttérsíkot rögzíti a térben. A 3D pont 3 float értékből álló tömbként van ábrázolva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Visszaad vagy beállít egy fel felé mutató vektort. Pontosabban, ez az attribútum egy vektort definiál, amely a háttérsík felületéhez viszonyítva a fel felé mutat. A vektor 3 float értékből álló tömbként van ábrázolva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Visszatérési érték:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Visszaad vagy beállít egy fel felé mutató vektort. Pontosabban, ez az attribútum egy vektort definiál, amely a háttérsík felületéhez viszonyítva a fel felé mutat. A vektor 3 float értékből álló tömbként van ábrázolva, amely meghatározza az X, Y és Z koordinátákat. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |
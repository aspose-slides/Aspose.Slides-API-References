---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Meghatároz egy síkot, amelyben olyan hatások, mint a ragyogás és az árnyék, a rájuk alkalmazott alakzathoz viszonyítottan kerülnek alkalmazásra.
type: docs
url: /hu/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Meghatároz egy síkot, amelyben olyan hatások, mint a ragyogás és az árnyék, a rájuk alkalmazott alakzathoz viszonyítottan kerülnek alkalmazásra.
## Metódusok

| Metódus | Leírás |
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


Visszaad vagy beállít egy normál vektort. Pontosabban ez az attribútum egy olyan vektort definiál, amely a háttérsík felületére merőleges. A vektor 3 lebegőpontos értékből álló tömbként van ábrázolva, amelyek az X, Y és Z koordinátákat határozzák meg. Olvasás/írás float[].

**Visszatérési érték:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


Visszaad vagy beállít egy normál vektort. Pontosabban ez az attribútum egy olyan vektort definiál, amely a háttérsík felületére merőleges. A vektor 3 lebegőpontos értékből álló tömbként van ábrázolva, amelyek az X, Y és Z koordinátákat határozzák meg. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


Visszaad vagy beállít egy pontot a 3D térben. Ez a pont az a pont a térben, amely a háttérsíkot rögzíti. A 3D pont 3 lebegőpontos értékből álló tömbként van ábrázolva, amelyek az X, Y és Z koordinátákat határozzák meg. Olvasás/írás float[].

**Visszatérési érték:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


Visszaad vagy beállít egy pontot a 3D térben. Ez a pont az a pont a térben, amely a háttérsíkot rögzíti. A 3D pont 3 lebegőpontos értékből álló tömbként van ábrázolva, amelyek az X, Y és Z koordinátákat határozzák meg. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


Visszaad vagy beállít egy felfelé mutató vektort. Pontosabban ez az attribútum egy felfelé mutató vektort definiál a háttérsík felületéhez viszonyítva. A vektor 3 lebegőpontos értékből álló tömbként van ábrázolva, amelyek az X, Y és Z koordinátákat határozzák meg. Olvasás/írás float[].

**Visszatérési érték:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


Visszaad vagy beállít egy felfelé mutató vektort. Pontosabban ez az attribútum egy felfelé mutató vektort definiál a háttérsík felületéhez viszonyítva. A vektor 3 lebegőpontos értékből álló tömbként van ábrázolva, amelyek az X, Y és Z koordinátákat határozzák meg. Olvasás/írás float[].

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float[] |  |
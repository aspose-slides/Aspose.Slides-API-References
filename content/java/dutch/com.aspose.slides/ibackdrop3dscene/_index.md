---
title: IBackdrop3DScene
second_title: Aspose.Slides voor Java API-referentie
description: Definieert een vlak waarin effecten zoals gloed en schaduw worden toegepast in relatie tot de vorm waarop ze worden toegepast.
type: docs
url: /nl/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Definieert een vlak waarin effecten, zoals gloed en schaduw, worden toegepast in relatie tot de vorm waarop ze worden toegepast.
## Methoden

| Method | Description |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Geeft een normale vector terug of stelt deze in. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Geeft een normale vector terug of stelt deze in. |
| [getAnchorPoint()](#getAnchorPoint--) | Geeft een punt in 3D-ruimte terug of stelt dit in. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Geeft een punt in 3D-ruimte terug of stelt dit in. |
| [getUpVector()](#getUpVector--) | Geeft een vector die omhoog wijst terug of stelt deze in. |
| [setUpVector(float[] value)](#setUpVector-float---) | Geeft een vector die omhoog wijst terug of stelt deze in. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Geeft een normale vector terug of stelt deze in. Om preciezer te zijn, definieert dit attribuut een vector die loodrecht staat op het vlak van de achtergrond. De vector wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Retour:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Geeft een normale vector terug of stelt deze in. Om preciezer te zijn, definieert dit attribuut een vector die loodrecht staat op het vlak van de achtergrond. De vector wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Geeft een punt in 3D-ruimte terug of stelt dit in. Dit punt is het punt in de ruimte dat het achtergrondvlak verankert. Het 3D-punt wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Retour:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Geeft een punt in 3D-ruimte terug of stelt dit in. Dit punt is het punt in de ruimte dat het achtergrondvlak verankert. Het 3D-punt wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Geeft een vector die omhoog wijst terug of stelt deze in. Om preciezer te zijn, definieert dit attribuut een vector die omhoog wijst in relatie tot het vlak van de achtergrond. De vector wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Retour:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Geeft een vector die omhoog wijst terug of stelt deze in. Om preciezer te zijn, definieert dit attribuut een vector die omhoog wijst in relatie tot het vlak van de achtergrond. De vector wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |
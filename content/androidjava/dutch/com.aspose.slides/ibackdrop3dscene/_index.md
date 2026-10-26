---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Definieert een vlak waarin effecten zoals gloed en schaduw worden toegepast in relatie tot de vorm waarop ze worden toegepast.
type: docs
url: /nl/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Definieert een vlak waarin effecten, zoals gloed en schaduw, worden toegepast in relatie tot de vorm waarop ze worden toegepast.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Retourneert of stelt een normale vector in. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Retourneert of stelt een normale vector in. |
| [getAnchorPoint()](#getAnchorPoint--) | Retourneert of stelt een punt in 3D-ruimte in. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Retourneert of stelt een punt in 3D-ruimte in. |
| [getUpVector()](#getUpVector--) | Retourneert of stelt een vector die omhoog aangeeft in. |
| [setUpVector(float[] value)](#setUpVector-float---) | Retourneert of stelt een vector die omhoog aangeeft in. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Retourneert of stelt een normale vector in. Om preciezer te zijn, definieert dit attribuut een vector die normaal is op het vlak van de achtergrond. Vector wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Retourneert:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Retourneert of stelt een normale vector in. Om preciezer te zijn, definieert dit attribuut een vector die normaal is op het vlak van de achtergrond. Vector wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Retourneert of stelt een punt in 3D-ruimte in. Dit punt is het punt in de ruimte dat het achtergrondvlak verankert. 3D-punt wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Retourneert:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Retourneert of stelt een punt in 3D-ruimte in. Dit punt is het punt in de ruimte dat het achtergrondvlak verankert. 3D-punt wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Retourneert of stelt een vector die omhoog aangeeft in. Om preciezer te zijn, definieert dit attribuut een vector die omhoog aangeeft in relatie tot het vlak van de achtergrond. Vector wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Retourneert:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Retourneert of stelt een vector die omhoog aangeeft in. Om preciezer te zijn, definieert dit attribuut een vector die omhoog aangeeft in relatie tot het vlak van de achtergrond. Vector wordt weergegeven door een array van 3 float-waarden die de X-, Y- en Z-coördinaten definiëren. Lezen/schrijven float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |
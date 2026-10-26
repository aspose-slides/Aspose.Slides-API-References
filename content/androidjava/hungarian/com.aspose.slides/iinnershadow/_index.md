---
title: IInnerShadow
second_title: Aspose.Slides for Android a Java API referenciához
description: Belső árnyékhatást ábrázol.
type: docs
url: /hu/com.aspose.slides/iinnershadow/
---
**Megvalósított interfészek:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

Belső árnyékhatást ábrázol.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Elmosódási sugár. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Elmosódási sugár. |
| [getDirection()](#getDirection--) | Árnyék iránya. |
| [setDirection(float value)](#setDirection-float-) | Árnyék iránya. |
| [getDistance()](#getDistance--) | Árnyék távolsága. |
| [setDistance(double value)](#setDistance-double-) | Árnyék távolsága. |
| [getShadowColor()](#getShadowColor--) | Árnyék színe. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

Elmosódási sugár. Olvasás/írás double.

**Visszatérési érték:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

Elmosódási sugár. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Árnyék iránya. Olvasás/írás float.

**Visszatérési érték:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

Árnyék iránya. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Árnyék távolsága. Olvasás/írás double.

**Visszatérési érték:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

Árnyék távolsága. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

Árnyék színe. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
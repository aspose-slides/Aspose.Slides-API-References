---
title: IBlur
second_title: Odwołanie do API Aspose.Slides dla Javy
description: Reprezentuje efekt rozmycia, który jest stosowany do całego kształtu, włącznie z jego wypełnieniem.
type: docs
url: /pl/com.aspose.slides/iblur/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRadius()](#getRadius--) | Returns or sets blur radius. |
| [setRadius(double value)](#setRadius-double-) | Returns or sets blur radius. |
| [getGrow()](#getGrow--) | Determines whether the bounds of the object should be grown as a result of the blurring. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determines whether the bounds of the object should be grown as a result of the blurring. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Returns or sets blur radius. Read/write double.

**Zwraca:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Returns or sets blur radius. Read/write double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Determines whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. Read/write boolean.

**Zwraca:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Determines whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. Read/write boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
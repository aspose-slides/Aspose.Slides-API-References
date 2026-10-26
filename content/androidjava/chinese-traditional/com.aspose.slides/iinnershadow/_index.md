---
title: IInnerShadow
second_title: Aspose.Slides for Android via Java API 參考
description: 表示內部陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/iinnershadow/
---
**所有已實作的介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IInnerShadow extends IImageTransformOperation, IAccessiblePVIObject<IInnerShadowEffectiveData>
```

表示內部陰影效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半徑。 |
| [getDirection()](#getDirection--) | 陰影方向。 |
| [setDirection(float value)](#setDirection-float-) | 陰影方向。 |
| [getDistance()](#getDistance--) | 陰影距離。 |
| [setDistance(double value)](#setDistance-double-) | 陰影距離。 |
| [getShadowColor()](#getShadowColor--) | 陰影顏色。 |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


模糊半徑。可讀寫 double.

**返回：**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


模糊半徑。可讀寫 double.

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


陰影方向。可讀寫 float.

**返回：**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


陰影方向。可讀寫 float.

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


陰影距離。可讀寫 double.

**返回：**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


陰影距離。可讀寫 double.

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


陰影顏色。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
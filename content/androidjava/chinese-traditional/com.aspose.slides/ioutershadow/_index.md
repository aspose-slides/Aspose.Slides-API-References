---
title: IOuterShadow
second_title: Aspose.Slides for Android via Java API 參考
description: 表示外部陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/ioutershadow/
---
**所有已實作的介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

表示外部陰影效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑，以點為單位。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半徑，以點為單位。 |
| [getDirection()](#getDirection--) | 陰影方向，以度為單位。 |
| [setDirection(float value)](#setDirection-float-) | 陰影方向，以度為單位。 |
| [getDistance()](#getDistance--) | 陰影與物件之間的距離，以點為單位。 |
| [setDistance(double value)](#setDistance-double-) | 陰影與物件之間的距離，以點為單位。 |
| [getShadowColor()](#getShadowColor--) | 陰影的顏色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形對齊方式。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形對齊方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 水平斜切角度，以度為單位。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 水平斜切角度，以度為單位。 |
| [getSkewVertical()](#getSkewVertical--) | 垂直斜切角度，以度為單位。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 垂直斜切角度，以度為單位。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指示陰影是否隨形狀一起旋轉。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指示陰影是否隨形狀一起旋轉。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 水平縮放係數，以原始尺寸的百分比表示。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 水平縮放係數，以原始尺寸的百分比表示。 |
| [getScaleVertical()](#getScaleVertical--) | 垂直縮放係數，以原始尺寸的百分比表示。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 垂直縮放係數，以原始尺寸的百分比表示。 |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

模糊半徑，以點為單位。預設值為 0 pt。可讀寫 double。

**返回：**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

模糊半徑，以點為單位。預設值為 0 pt。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

陰影方向，以度為單位。預設值為 0 � (從左到右)。可讀寫 float。

**返回：**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

陰影方向，以度為單位。預設值為 0 � (從左到右)。可讀寫 float。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

陰影與物件之間的距離，以點為單位。預設值為 0 pt。可讀寫 double。

**返回：**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

陰影與物件之間的距離，以點為單位。預設值為 0 pt。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

陰影的顏色。預設值為自動黑色（取決於主題）。唯讀 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形對齊方式。預設值為 [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。可讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**返回：**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

矩形對齊方式。預設值為 [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。可讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

水平斜切角度，以度為單位。預設值為 0 �。可讀寫 double。

**返回：**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

水平斜切角度，以度為單位。預設值為 0 �。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

垂直斜切角度，以度為單位。預設值為 0 �。可讀寫 double。

**返回：**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

垂直斜切角度，以度為單位。預設值為 0 �。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

指示陰影是否隨形狀一起旋轉。預設值為 true。可讀寫 boolean。

**返回：**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

指示陰影是否隨形狀一起旋轉。預設值為 true。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

水平縮放係數，以原始尺寸的百分比表示。負縮放會導致翻轉。預設值為 100%。可讀寫 double。

**返回：**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

水平縮放係數，以原始尺寸的百分比表示。負縮放會導致翻轉。預設值為 100%。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

垂直縮放係數，以原始尺寸的百分比表示。負縮放會導致翻轉。預設值為 100%。可讀寫 double。

**返回：**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

垂直縮放係數，以原始尺寸的百分比表示。負縮放會導致翻轉。預設值為 100%。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
---
title: IReflection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示反射效果。
type: docs
url: /zh-hant/com.aspose.slides/ireflection/
---
**所有已實作的介面：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IReflection extends IImageTransformOperation, IAccessiblePVIObject<IReflectionEffectiveData>
```

表示反射效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 指定起始 alpha 值（百分比）的起始位置（沿 alpha 漸層坡道）。 |
| [setStartPosAlpha(float value)](#setStartPosAlpha-float-) | 指定起始 alpha 值（百分比）的起始位置（沿 alpha 漸層坡道）。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | 指定結束 alpha 值（百分比）的結束位置（沿 alpha 漸層坡道）。 |
| [setEndPosAlpha(float value)](#setEndPosAlpha-float-) | 指定結束 alpha 值（百分比）的結束位置（沿 alpha 漸層坡道）。 |
| [getFadeDirection()](#getFadeDirection--) | 指定反射的偏移方向。 |
| [setFadeDirection(float value)](#setFadeDirection-float-) | 指定反射的偏移方向。 |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 起始反射不透明度。（百分比） |
| [setStartReflectionOpacity(float value)](#setStartReflectionOpacity-float-) | 起始反射不透明度。（百分比） |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 結束反射不透明度。（百分比） |
| [setEndReflectionOpacity(float value)](#setEndReflectionOpacity-float-) | 結束反射不透明度。（百分比） |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | 模糊半徑。 |
| [getDirection()](#getDirection--) | 反射方向。 |
| [setDirection(float value)](#setDirection-float-) | 反射方向。 |
| [getDistance()](#getDistance--) | 反射距離。 |
| [setDistance(double value)](#setDistance-double-) | 反射距離。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形對齊。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形對齊。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 指定水平斜角。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 指定水平斜角。 |
| [getSkewVertical()](#getSkewVertical--) | 指定垂直斜角。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 指定垂直斜角。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指定當形狀旋轉時，反射是否應隨形狀一起旋轉。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | 指定當形狀旋轉時，反射是否應隨形狀一起旋轉。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 指定水平縮放係數，負的縮放會導致翻轉。（百分比） |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 指定水平縮放係數，負的縮放會導致翻轉。（百分比） |
| [getScaleVertical()](#getScaleVertical--) | 指定垂直縮放係數，負的縮放會導致翻轉。（百分比） |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 指定垂直縮放係數，負的縮放會導致翻轉。（百分比） |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

指定起始 alpha 值（百分比）的起始位置（沿 alpha 漸層坡道）。 讀寫 float。

**傳回值：**
float
### setStartPosAlpha(float value) {#setStartPosAlpha-float-}
```
public abstract void setStartPosAlpha(float value)
```

指定起始 alpha 值（百分比）的起始位置（沿 alpha 漸層坡道）。 讀寫 float。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | float |  |
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

指定結束 alpha 值（百分比）的結束位置（沿 alpha 漸層坡道）。 讀寫 float。

**傳回值：**
float
### setEndPosAlpha(float value) {#setEndPosAlpha-float-}
```
public abstract void setEndPosAlpha(float value)
```

指定結束 alpha 值（百分比）的結束位置（沿 alpha 漸層坡道）。 讀寫 float。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | float |  |
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

指定反射的偏移方向。（角度） 讀寫 float。

**傳回值：**
float
### setFadeDirection(float value) {#setFadeDirection-float-}
```
public abstract void setFadeDirection(float value)
```

指定反射的偏移方向。（角度） 讀寫 float。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | float |  |
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

起始反射不透明度。（百分比） 讀寫 float。

**傳回值：**
float
### setStartReflectionOpacity(float value) {#setStartReflectionOpacity-float-}
```
public abstract void setStartReflectionOpacity(float value)
```

起始反射不透明度。（百分比） 讀寫 float。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | float |  |
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

結束反射不透明度。（百分比） 讀寫 float。

**傳回值：**
float
### setEndReflectionOpacity(float value) {#setEndReflectionOpacity-float-}
```
public abstract void setEndReflectionOpacity(float value)
```

結束反射不透明度。（百分比） 讀寫 float。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | float |  |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

模糊半徑。 讀寫 double。

**傳回值：**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

模糊半徑。 讀寫 double。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

反射方向。 讀寫 float。

**傳回值：**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

反射方向。 讀寫 float。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

反射距離。 讀寫 double。

**傳回值：**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

反射距離。 讀寫 double。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | double |  |
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

矩形對齊。 讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**傳回值：**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

矩形對齊。 讀寫 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

指定水平斜角。 讀寫 double。

**傳回值：**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

指定水平斜角。 讀寫 double。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

指定垂直斜角。 讀寫 double。

**傳回值：**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

指定垂直斜角。 讀寫 double。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

指定當形狀旋轉時，反射是否應隨形狀一起旋轉。 讀寫 boolean。

**傳回值：**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

指定當形狀旋轉時，反射是否應隨形狀一起旋轉。 讀寫 boolean。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

指定水平縮放係數，負的縮放會導致翻轉。（百分比） 讀寫 double。

**傳回值：**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

指定水平縮放係數，負的縮放會導致翻轉。（百分比） 讀寫 double。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

指定垂直縮放係數，負的縮放會導致翻轉。（百分比） 讀寫 double。

**傳回值：**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

指定垂直縮放係數，負的縮放會導致翻轉。（百分比） 讀寫 double。

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | double |  |
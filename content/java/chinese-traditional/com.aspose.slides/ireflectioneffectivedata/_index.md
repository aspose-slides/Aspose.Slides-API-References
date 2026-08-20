---
title: IReflectionEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變的物件，表示 Reflection 效果。
type: docs
url: /zh-hant/com.aspose.slides/ireflectioneffectivedata/
---
**已實作的介面:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

不可變的物件，表示 Reflection 效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | 指定起始 alpha 值 (percents) 在 alpha 漸層坡道上的起始位置 (percents)。 |
| [getEndPosAlpha()](#getEndPosAlpha--) | 指定結束 alpha 值 (percents) 在 alpha 漸層坡道上的結束位置 (percents)。 |
| [getFadeDirection()](#getFadeDirection--) | 指定反射的偏移方向。 |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | 起始反射不透明度。 |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | 結束反射不透明度。 |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑。 |
| [getDirection()](#getDirection--) | 反射方向。 |
| [getDistance()](#getDistance--) | 反射距離。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形對齊方式。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 指定水平斜切角度。 |
| [getSkewVertical()](#getSkewVertical--) | 指定垂直斜切角度。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指定在形狀旋轉時，反射是否隨形狀一起旋轉。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 指定水平縮放因子，負值縮放會導致翻轉。 |
| [getScaleVertical()](#getScaleVertical--) | 指定垂直縮放因子，負值縮放會導致翻轉。 |
### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```


指定起始 alpha 值 (percents) 在 alpha 漸層坡道上的起始位置 (percents)。唯讀 float。

**返回:**
float
### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```


指定結束 alpha 值 (percents) 在 alpha 漸層坡道上的結束位置 (percents)。唯讀 float。

**返回:**
float
### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```


指定偏移反射的方向 (角度)。唯讀 float。

**返回:**
float
### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```


起始反射不透明度 (percents)。唯讀 float。

**返回:**
float
### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```


結束反射不透明度 (percents)。唯讀 float。

**返回:**
float
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


模糊半徑。唯讀 double。

**返回:**
double
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


反射方向。唯讀 float。

**返回:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


反射距離。唯讀 double。

**返回:**
double
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


矩形對齊方式。唯讀 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**返回:**
byte
### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


指定水平斜切角度。唯讀 double。

**返回:**
double
### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


指定垂直斜切角度。唯讀 double。

**返回:**
double
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


指定在形狀旋轉時，反射是否隨形狀一起旋轉。唯讀 boolean。

**返回:**
boolean
### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


指定水平縮放因子 (percents)。唯讀 double。

**返回:**
double
### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


指定垂直縮放因子 (percents)。唯讀 double。

**返回:**
double
---
title: IOuterShadowEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變的物件，表示外部陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/ioutershadoweffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IOuterShadowEffectiveData extends IEffectEffectiveData
```

不可變的物件，表示外部陰影效果。

## 方法

| Method | Description |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | 模糊半徑。 |
| [getDirection()](#getDirection--) | 陰影方向。 |
| [getDistance()](#getDistance--) | 陰影距離。 |
| [getShadowColor()](#getShadowColor--) | 陰影顏色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形對齊。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 指定水平斜切角度（以度為單位）。 |
| [getSkewVertical()](#getSkewVertical--) | 指定垂直斜切角度（以度為單位）。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | 指定當形狀旋轉時陰影是否隨形狀一起旋轉。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 指定水平縮放係數，負值會產生翻轉。 |
| [getScaleVertical()](#getScaleVertical--) | 指定垂直縮放係數，負值會產生翻轉。 |

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


模糊半徑。唯讀 double.

**返回：**
double

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


陰影方向。唯讀 float.

**返回：**
float

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


陰影距離。唯讀 double.

**返回：**
double

### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```


陰影顏色。唯讀 java.awt.Color.

**返回：**
java.awt.Color

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


矩形對齊。唯讀 [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**返回：**
byte

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


指定水平斜切角度（以度為單位）。唯讀 double.

**返回：**
double

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


指定垂直斜切角度（以度為單位）。唯讀 double.

**返回：**
double

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


指定當形狀旋轉時陰影是否隨形狀一起旋轉。唯讀 boolean.

**返回：**
boolean

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


指定水平縮放係數，負值會產生翻轉。唯讀 double.

**返回：**
double

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


指定垂直縮放係數，負值會產生翻轉。唯讀 double.

**返回：**
double
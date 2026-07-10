---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 参考
description: 不可变对象，包含有效的渐变填充属性。
type: docs
url: /zh/com.aspose.slides/igradientformateffectivedata/
---
**所有实现的接口：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

不可变对象，包含有效的渐变填充属性。

--------------------

此接口用作 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) 和 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | 返回渐变的翻转模式。 |
| [getGradientDirection()](#getGradientDirection--) | 返回渐变的样式。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 返回渐变的角度。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 确定渐变是否已缩放。 |
| [getGradientShape()](#getGradientShape--) | 返回渐变的形状。 |
| [getGradientStops()](#getGradientStops--) | 返回渐变停止点的集合。 |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


返回渐变的翻转模式。只读 [TileFlip](../../com.aspose.slides/tileflip).

**返回：**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


返回渐变的样式。只读 [GradientDirection](../../com.aspose.slides/gradientdirection).

**返回：**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


返回渐变的角度。只读 float.

**返回：**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```


确定渐变是否已缩放。只读 boolean.

**返回：**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


返回渐变的形状。只读 [GradientShape](../../com.aspose.slides/gradientshape).

**返回：**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```


返回渐变停止点的集合。只读 [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata).

**返回：**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
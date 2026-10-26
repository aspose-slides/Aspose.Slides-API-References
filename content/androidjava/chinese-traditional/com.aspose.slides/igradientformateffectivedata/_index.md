---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變對象，包含有效的漸層填充屬性。
type: docs
url: /zh-hant/com.aspose.slides/igradientformateffectivedata/
---
**所有已實現的介面：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

不可變對象，包含有效的漸層填充屬性。

--------------------

此介面作為 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) 與 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) 的一部分使用。
## 方法

| Method | Description |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | 返回漸層的翻轉模式。 |
| [getGradientDirection()](#getGradientDirection--) | 返回漸層的樣式。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 返回漸層的角度。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 判斷漸層是否被縮放。 |
| [getGradientShape()](#getGradientShape--) | 返回漸層的形狀。 |
| [getGradientStops()](#getGradientStops--) | 返回漸層停止點的集合。 |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

返回漸層的翻轉模式。唯讀 [TileFlip](../../com.aspose.slides/tileflip)。

**返回：**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

返回漸層的樣式。唯讀 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**返回：**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

返回漸層的角度。唯讀 float。

**返回：**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

判斷漸層是否被縮放。唯讀 boolean。

**返回：**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

返回漸層的形狀。唯讀 [GradientShape](../../com.aspose.slides/gradientshape)。

**返回：**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

返回漸層停止點的集合。唯讀 [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)。

**返回：**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
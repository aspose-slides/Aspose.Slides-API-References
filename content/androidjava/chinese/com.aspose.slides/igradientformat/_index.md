---
title: IGradientFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种梯度格式。
type: docs
url: /zh/com.aspose.slides/igradientformat/
---
**所有已实现的接口：**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

表示一种梯度格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | 返回或设置梯度的翻转模式。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 返回或设置梯度的翻转模式。 |
| [getGradientDirection()](#getGradientDirection--) | 返回或设置梯度的样式。 |
| [setGradientDirection(int value)](#setGradientDirection-int-) | 返回或设置梯度的样式。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 返回或设置梯度的角度。 |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | 返回或设置梯度的角度。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 确定梯度是否已缩放。 |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | 确定梯度是否已缩放。 |
| [getGradientShape()](#getGradientShape--) | 返回或设置梯度的形状。 |
| [setGradientShape(byte value)](#setGradientShape-byte-) | 返回或设置梯度的形状。 |
| [getGradientStops()](#getGradientStops--) | 返回梯度停止点的集合。 |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

返回或设置梯度的翻转模式。 读/写 [TileFlip](../../com.aspose.slides/tileflip)。

**返回：**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

返回或设置梯度的翻转模式。 读/写 [TileFlip](../../com.aspose.slides/tileflip)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

返回或设置梯度的样式。 读/写 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**返回：**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

返回或设置梯度的样式。 读/写 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

返回或设置梯度的角度。 读/写 float。

**返回：**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

返回或设置梯度的角度。 读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

确定梯度是否已缩放。 读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

确定梯度是否已缩放。 读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

返回或设置梯度的形状。 读/写 [GradientShape](../../com.aspose.slides/gradientshape)。

**返回：**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

返回或设置梯度的形状。 读/写 [GradientShape](../../com.aspose.slides/gradientshape)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

返回梯度停止点的集合。 只读 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)。

**返回：**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
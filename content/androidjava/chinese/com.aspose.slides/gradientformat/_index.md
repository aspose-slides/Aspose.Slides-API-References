---
title: GradientFormat
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示梯度格式。
type: docs
url: /zh/com.aspose.slides/gradientformat/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已实现的接口：**
[com.aspose.slides.IGradientFormat](../../com.aspose.slides/igradientformat)
```
public final class GradientFormat extends PVIObject implements IGradientFormat
```

表示梯度格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTileFlip()](#getTileFlip--) | 返回或设置梯度的翻转模式。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 返回或设置梯度的翻转模式。 |
| [getGradientDirection()](#getGradientDirection--) | 返回或设置梯度的样式。 |
| [setGradientDirection(int value)](#setGradientDirection-int-) | 返回或设置梯度的样式。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 返回或设置梯度的角度。 |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | 返回或设置梯度的角度。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 确定梯度是否缩放。 |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | 确定梯度是否缩放。 |
| [getGradientShape()](#getGradientShape--) | 返回或设置梯度的形状。 |
| [setGradientShape(byte value)](#setGradientShape-byte-) | 返回或设置梯度的形状。 |
| [getGradientStops()](#getGradientStops--) | 返回梯度停止点的集合。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. 只读 long.

**返回：**
long
### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```


返回或设置梯度的翻转模式。 读写 [TileFlip](../../com.aspose.slides/tileflip).

**返回：**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```


返回或设置梯度的翻转模式。 读写 [TileFlip](../../com.aspose.slides/tileflip).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getGradientDirection() {#getGradientDirection--}
```
public final int getGradientDirection()
```


返回或设置梯度的样式。 读写 [GradientDirection](../../com.aspose.slides/gradientdirection).

**返回：**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public final void setGradientDirection(int value)
```


返回或设置梯度的样式。 读写 [GradientDirection](../../com.aspose.slides/gradientdirection).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public final float getLinearGradientAngle()
```


返回或设置梯度的角度。 读写 float.

**返回：**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public final void setLinearGradientAngle(float value)
```


返回或设置梯度的角度。 读写 float.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public final byte getLinearGradientScaled()
```


确定梯度是否缩放。 读写 [NullableBool](../../com.aspose.slides/nullablebool).

**返回：**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public final void setLinearGradientScaled(byte value)
```


确定梯度是否缩放。 读写 [NullableBool](../../com.aspose.slides/nullablebool).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getGradientShape() {#getGradientShape--}
```
public final byte getGradientShape()
```


返回或设置梯度的形状。 读写 [GradientShape](../../com.aspose.slides/gradientshape).

**返回：**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public final void setGradientShape(byte value)
```


返回或设置梯度的形状。 读写 [GradientShape](../../com.aspose.slides/gradientshape).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getGradientStops() {#getGradientStops--}
```
public final IGradientStopCollection getGradientStops()
```


返回梯度停止点的集合。 只读 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**返回：**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
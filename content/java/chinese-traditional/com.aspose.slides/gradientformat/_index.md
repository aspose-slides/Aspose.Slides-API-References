---
title: GradientFormat
second_title: Aspose.Slides for Java API 參考
description: 表示梯度格式。
type: docs
url: /zh-hant/com.aspose.slides/gradientformat/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有實作的介面:**  
[com.aspose.slides.IGradientFormat](../../com.aspose.slides/igradientformat)  
```
public final class GradientFormat extends PVIObject implements IGradientFormat
```

表示梯度格式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTileFlip()](#getTileFlip--) | 取得或設定梯度的翻轉模式。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 取得或設定梯度的翻轉模式。 |
| [getGradientDirection()](#getGradientDirection--) | 取得或設定梯度的樣式。 |
| [setGradientDirection(int value)](#setGradientDirection-int-) | 取得或設定梯度的樣式。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 取得或設定梯度的角度。 |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | 取得或設定梯度的角度。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 判斷梯度是否已縮放。 |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | 判斷梯度是否已縮放。 |
| [getGradientShape()](#getGradientShape--) | 取得或設定梯度的形狀。 |
| [setGradientShape(byte value)](#setGradientShape-byte-) | 取得或設定梯度的形狀。 |
| [getGradientStops()](#getGradientStops--) | 取得梯度停止點的集合。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只讀 long。

**傳回：**  
long

### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```

取得或設定梯度的翻轉模式。可讀寫 [TileFlip](../../com.aspose.slides/tileflip)。

**傳回：**  
int

### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```

取得或設定梯度的翻轉模式。可讀寫 [TileFlip](../../com.aspose.slides/tileflip)。

**參數：**  

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public final int getGradientDirection()
```

取得或設定梯度的樣式。可讀寫 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**傳回：**  
int

### setGradientDirection(int value) {#setGradientDirection-int-}
```
public final void setGradientDirection(int value)
```

取得或設定梯度的樣式。可讀寫 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**參數：**  

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public final float getLinearGradientAngle()
```

取得或設定梯度的角度。可讀寫 float。

**傳回：**  
float

### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public final void setLinearGradientAngle(float value)
```

取得或設定梯度的角度。可讀寫 float。

**參數：**  

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public final byte getLinearGradientScaled()
```

判斷梯度是否已縮放。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回：**  
byte

### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public final void setLinearGradientScaled(byte value)
```

判斷梯度是否已縮放。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**  

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public final byte getGradientShape()
```

取得或設定梯度的形狀。可讀寫 [GradientShape](../../com.aspose.slides/gradientshape)。

**傳回：**  
byte

### setGradientShape(byte value) {#setGradientShape-byte-}
```
public final void setGradientShape(byte value)
```

取得或設定梯度的形狀。可讀寫 [GradientShape](../../com.aspose.slides/gradientshape)。

**參數：**  

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public final IGradientStopCollection getGradientStops()
```

取得梯度停止點的集合。只讀 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)。

**傳回：**  
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
---
title: IGradientFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示梯度格式。
type: docs
url: /zh-hant/com.aspose.slides/igradientformat/
---
**所有已實作的介面**：
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

表示梯度格式。
## 方法

| 方法 | 說明 |
| --- | --- |
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
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```


取得或設定梯度的翻轉模式。讀寫 [TileFlip](../../com.aspose.slides/tileflip)。

**回傳:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```


取得或設定梯度的翻轉模式。讀寫 [TileFlip](../../com.aspose.slides/tileflip)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```


取得或設定梯度的樣式。讀寫 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**回傳:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```


取得或設定梯度的樣式。讀寫 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```


取得或設定梯度的角度。讀寫 float。

**回傳:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```


取得或設定梯度的角度。讀寫 float。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```


判斷梯度是否已縮放。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**回傳:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```


判斷梯度是否已縮放。讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```


取得或設定梯度的形狀。讀寫 [GradientShape](../../com.aspose.slides/gradientshape)。

**回傳:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```


取得或設定梯度的形狀。讀寫 [GradientShape](../../com.aspose.slides/gradientshape)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```


取得梯度停止點的集合。唯讀 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)。

**回傳:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
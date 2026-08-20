---
title: IGradientFormat
second_title: Aspose.Slides for Java API 參考
description: 表示漸層格式。
type: docs
url: /zh-hant/com.aspose.slides/igradientformat/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

表示漸層格式。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | 返回或設定漸層的翻轉模式。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 返回或設定漸層的翻轉模式。 |
| [getGradientDirection()](#getGradientDirection--) | 返回或設定漸層的樣式。 |
| [setGradientDirection(int value)](#setGradientDirection-int-) | 返回或設定漸層的樣式。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 返回或設定漸層的角度。 |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | 返回或設定漸層的角度。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 判斷漸層是否已縮放。 |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | 判斷漸層是否已縮放。 |
| [getGradientShape()](#getGradientShape--) | 返回或設定漸層的形狀。 |
| [setGradientShape(byte value)](#setGradientShape-byte-) | 返回或設定漸層的形狀。 |
| [getGradientStops()](#getGradientStops--) | 返回漸層停止點的集合。 |

### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

返回或設定漸層的翻轉模式。可讀寫 [TileFlip](../../com.aspose.slides/tileflip)。

**返回:**  
int

### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

返回或設定漸層的翻轉模式。可讀寫 [TileFlip](../../com.aspose.slides/tileflip)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

返回或設定漸層的樣式。可讀寫 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**返回:**  
int

### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

返回或設定漸層的樣式。可讀寫 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

返回或設定漸層的角度。可讀寫 float。

**返回:**  
float

### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

返回或設定漸層的角度。可讀寫 float。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

判斷漸層是否已縮放。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

判斷漸層是否已縮放。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

返回或設定漸層的形狀。可讀寫 [GradientShape](../../com.aspose.slides/gradientshape)。

**返回:**  
byte

### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

返回或設定漸層的形狀。可讀寫 [GradientShape](../../com.aspose.slides/gradientshape)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

返回漸層停止點的集合。唯讀 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)。

**返回:**  
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
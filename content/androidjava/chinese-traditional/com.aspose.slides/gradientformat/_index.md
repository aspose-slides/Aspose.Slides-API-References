---
title: GradientFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示漸層格式。
type: docs
url: /zh-hant/com.aspose.slides/gradientformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IGradientFormat](../../com.aspose.slides/igradientformat)
```
public final class GradientFormat extends PVIObject implements IGradientFormat
```

表示漸層格式。
## Methods

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTileFlip()](#getTileFlip--) | 取得或設定漸層的翻轉模式。 |
| [setTileFlip(int value)](#setTileFlip-int-) | 取得或設定漸層的翻轉模式。 |
| [getGradientDirection()](#getGradientDirection--) | 取得或設定漸層的樣式。 |
| [setGradientDirection(int value)](#setGradientDirection-int-) | 取得或設定漸層的樣式。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | 取得或設定漸層的角度。 |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | 取得或設定漸層的角度。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | 判斷漸層是否已縮放。 |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | 判斷漸層是否已縮放。 |
| [getGradientShape()](#getGradientShape--) | 取得或設定漸層的形狀。 |
| [setGradientShape(byte value)](#setGradientShape-byte-) | 取得或設定漸層的形狀。 |
| [getGradientStops()](#getGradientStops--) | 取得漸層停止點的集合。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**Returns:**
long
### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```

取得或設定漸層的翻轉模式。可讀寫 [TileFlip](../../com.aspose.slides/tileflip)。

**Returns:**
int
### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```

取得或設定漸層的翻轉模式。可讀寫 [TileFlip](../../com.aspose.slides/tileflip)。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public final int getGradientDirection()
```

取得或設定漸層的樣式。可讀寫 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**Returns:**
int
### setGradientDirection(int value) {#setGradientDirection-int-}
```
public final void setGradientDirection(int value)
```

取得或設定漸層的樣式。可讀寫 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public final float getLinearGradientAngle()
```

取得或設定漸層的角度。可讀寫 float。

**Returns:**
float
### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public final void setLinearGradientAngle(float value)
```

取得或設定漸層的角度。可讀寫 float。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public final byte getLinearGradientScaled()
```

判斷漸層是否已縮放。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**Returns:**
byte
### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public final void setLinearGradientScaled(byte value)
```

判斷漸層是否已縮放。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public final byte getGradientShape()
```

取得或設定漸層的形狀。可讀寫 [GradientShape](../../com.aspose.slides/gradientshape)。

**Returns:**
byte
### setGradientShape(byte value) {#setGradientShape-byte-}
```
public final void setGradientShape(byte value)
```

取得或設定漸層的形狀。可讀寫 [GradientShape](../../com.aspose.slides/gradientshape)。

**Parameters:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public final IGradientStopCollection getGradientStops()
```

取得漸層停止點的集合。唯讀 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)。

**Returns:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
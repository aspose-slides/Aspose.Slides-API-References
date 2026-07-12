---
title: GradientFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: グラデーション形式を表します。
type: docs
url: /ja/com.aspose.slides/gradientformat/
---
**Inheritance:**  
継承: java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
実装されているすべてのインターフェイス:  
[com.aspose.slides.IGradientFormat](../../com.aspose.slides/igradientformat)  
```
public final class GradientFormat extends PVIObject implements IGradientFormat
```

グラデーション形式を表します。

## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTileFlip()](#getTileFlip--) | グラデーションのフリッピングモードを取得または設定します。 |
| [setTileFlip(int value)](#setTileFlip-int-) | グラデーションのフリッピングモードを取得または設定します。 |
| [getGradientDirection()](#getGradientDirection--) | グラデーションのスタイルを取得または設定します。 |
| [setGradientDirection(int value)](#setGradientDirection-int-) | グラデーションのスタイルを取得または設定します。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | グラデーションの角度を取得または設定します。 |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | グラデーションの角度を取得または設定します。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | グラデーションがスケーリングされているかどうかを判定します。 |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | グラデーションがスケーリングされているかどうかを判定します。 |
| [getGradientShape()](#getGradientShape--) | グラデーションの形状を取得または設定します。 |
| [setGradientShape(byte value)](#setGradientShape-byte-) | グラデーションの形状を取得または設定します。 |
| [getGradientStops()](#getGradientStops--) | グラデーションストップのコレクションを取得します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。 読み取り専用 long.

**Returns:**  
long

### getTileFlip() {#getTileFlip--}
```
public final int getTileFlip()
```

グラデーションのフリッピングモードを取得または設定します。 読み取り/書き込み [TileFlip](../../com.aspose.slides/tileflip).

**Returns:**  
int

### setTileFlip(int value) {#setTileFlip-int-}
```
public final void setTileFlip(int value)
```

グラデーションのフリッピングモードを取得または設定します。 読み取り/書き込み [TileFlip](../../com.aspose.slides/tileflip).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public final int getGradientDirection()
```

グラデーションのスタイルを取得または設定します。 読み取り/書き込み [GradientDirection](../../com.aspose.slides/gradientdirection).

**Returns:**  
int

### setGradientDirection(int value) {#setGradientDirection-int-}
```
public final void setGradientDirection(int value)
```

グラデーションのスタイルを取得または設定します。 読み取り/書き込み [GradientDirection](../../com.aspose.slides/gradientdirection).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public final float getLinearGradientAngle()
```

グラデーションの角度を取得または設定します。 読み取り/書き込み float.

**Returns:**  
float

### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public final void setLinearGradientAngle(float value)
```

グラデーションの角度を取得または設定します。 読み取り/書き込み float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public final byte getLinearGradientScaled()
```

グラデーションがスケーリングされているかどうかを判定します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**  
byte

### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public final void setLinearGradientScaled(byte value)
```

グラデーションがスケーリングされているかどうかを判定します。 読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public final byte getGradientShape()
```

グラデーションの形状を取得または設定します。 読み取り/書き込み [GradientShape](../../com.aspose.slides/gradientshape).

**Returns:**  
byte

### setGradientShape(byte value) {#setGradientShape-byte-}
```
public final void setGradientShape(byte value)
```

グラデーションの形状を取得または設定します。 読み取り/書き込み [GradientShape](../../com.aspose.slides/gradientshape).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public final IGradientStopCollection getGradientStops()
```

グラデーションストップのコレクションを取得します。 読み取り専用 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection).

**Returns:**  
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
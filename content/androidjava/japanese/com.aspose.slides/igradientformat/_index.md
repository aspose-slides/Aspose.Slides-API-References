---
title: IGradientFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: グラデーション形式を表します。
type: docs
url: /ja/com.aspose.slides/igradientformat/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormat extends IFillParamSource
```

グラデーション形式を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | グラデーションのフリッピングモードを取得または設定します。 |
| [setTileFlip(int value)](#setTileFlip-int-) | グラデーションのフリッピングモードを取得または設定します。 |
| [getGradientDirection()](#getGradientDirection--) | グラデーションのスタイルを取得または設定します。 |
| [setGradientDirection(int value)](#setGradientDirection-int-) | グラデーションのスタイルを取得または設定します。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | グラデーションの角度を取得または設定します。 |
| [setLinearGradientAngle(float value)](#setLinearGradientAngle-float-) | グラデーションの角度を取得または設定します。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | グラデーションがスケールされているかどうかを判定します。 |
| [setLinearGradientScaled(byte value)](#setLinearGradientScaled-byte-) | グラデーションがスケールされているかどうかを判定します。 |
| [getGradientShape()](#getGradientShape--) | グラデーションの形状を取得または設定します。 |
| [setGradientShape(byte value)](#setGradientShape-byte-) | グラデーションの形状を取得または設定します。 |
| [getGradientStops()](#getGradientStops--) | グラデーションストップのコレクションを取得します。 |

### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

グラデーションのフリッピングモードを取得または設定します。読み取り/書き込み [TileFlip](../../com.aspose.slides/tileflip)。

**戻り値:**
int

### setTileFlip(int value) {#setTileFlip-int-}
```
public abstract void setTileFlip(int value)
```

グラデーションのフリッピングモードを取得または設定します。読み取り/書き込み [TileFlip](../../com.aspose.slides/tileflip)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

グラデーションのスタイルを取得または設定します。読み取り/書き込み [GradientDirection](../../com.aspose.slides/gradientdirection)。

**戻り値:**
int

### setGradientDirection(int value) {#setGradientDirection-int-}
```
public abstract void setGradientDirection(int value)
```

グラデーションのスタイルを取得または設定します。読み取り/書き込み [GradientDirection](../../com.aspose.slides/gradientdirection)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

グラデーションの角度を取得または設定します。読み取り/書き込み float。

**戻り値:**
float

### setLinearGradientAngle(float value) {#setLinearGradientAngle-float-}
```
public abstract void setLinearGradientAngle(float value)
```

グラデーションの角度を取得または設定します。読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract byte getLinearGradientScaled()
```

グラデーションがスケールされているかどうかを判定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setLinearGradientScaled(byte value) {#setLinearGradientScaled-byte-}
```
public abstract void setLinearGradientScaled(byte value)
```

グラデーションがスケールされているかどうかを判定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

グラデーションの形状を取得または設定します。読み取り/書き込み [GradientShape](../../com.aspose.slides/gradientshape)。

**戻り値:**
byte

### setGradientShape(byte value) {#setGradientShape-byte-}
```
public abstract void setGradientShape(byte value)
```

グラデーションの形状を取得または設定します。読み取り/書き込み [GradientShape](../../com.aspose.slides/gradientshape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollection getGradientStops()
```

グラデーションストップのコレクションを取得します。読み取り専用 [IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)。

**戻り値:**
[IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
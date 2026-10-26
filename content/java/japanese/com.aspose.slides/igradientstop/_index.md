---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: Represents a gradient format.
type: docs
url: /ja/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

グラデーション形式を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPosition()](#getPosition--) | グラデーション ストップの位置 (0..1) を取得または設定します。 |
| [setPosition(float value)](#setPosition-float-) | グラデーション ストップの位置 (0..1) を取得または設定します。 |
| [getColor()](#getColor--) | グラデーション ストップの色を取得します。 |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


グラデーション ストップの位置 (0..1) を取得または設定します。 読み書き可能な float。

**戻り値:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


グラデーション ストップの位置 (0..1) を取得または設定します。 読み書き可能な float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


グラデーション ストップの色を取得します。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
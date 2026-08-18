---
title: GradientStop
second_title: Aspose.Slides for Java API リファレンス
description: グラデーション形式を表します。
type: docs
url: /ja/com.aspose.slides/gradientstop/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)
```
public final class GradientStop extends PVIObject implements IGradientStop
```

グラデーション形式を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | グラデーション ストップの位置 (0..1) を取得または設定します。 |
| [setPosition(float value)](#setPosition-float-) | グラデーション ストップの位置 (0..1) を取得または設定します。 |
| [getColor()](#getColor--) | グラデーション ストップの色を取得します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long.

**戻り値:**
long
### getPosition() {#getPosition--}
```
public final float getPosition()
```

グラデーション ストップの位置 (0..1) を取得または設定します。読み書き  float .

**戻り値:**
float
### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```

グラデーション ストップの位置 (0..1) を取得または設定します。読み書き  float .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

グラデーション ストップの色を取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
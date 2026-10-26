---
title: IGradientFormatEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 効果的なグラデーション塗りつぶしプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/igradientformateffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

効果的なグラデーション塗りつぶしプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) と [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | グラデーションの反転モードを返します。 |
| [getGradientDirection()](#getGradientDirection--) | グラデーションのスタイルを返します。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | グラデーションの角度を返します。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | グラデーションがスケールされているかどうかを判定します。 |
| [getGradientShape()](#getGradientShape--) | グラデーションの形状を返します。 |
| [getGradientStops()](#getGradientStops--) | グラデーション停止点のコレクションを返します。 |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

グラデーションの反転モードを返します。読み取り専用 [TileFlip](../../com.aspose.slides/tileflip)。

**戻り値:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

グラデーションのスタイルを返します。読み取り専用 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**戻り値:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

グラデーションの角度を返します。読み取り専用 float。

**戻り値:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

グラデーションがスケールされているかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

グラデーションの形状を返します。読み取り専用 [GradientShape](../../com.aspose.slides/gradientshape)。

**戻り値:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

グラデーション停止点のコレクションを返します。読み取り専用 [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)。

**戻り値:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
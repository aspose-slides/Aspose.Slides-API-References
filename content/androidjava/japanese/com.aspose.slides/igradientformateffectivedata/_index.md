---
title: IGradientFormatEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 実効的なグラデーション塗りつぶしプロパティを含むイミュータブルオブジェクトです。
type: docs
url: /ja/com.aspose.slides/igradientformateffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IGradientFormatEffectiveData extends IFillParamSource
```

効果的なグラデーション塗りつぶしプロパティを含むイミュータブルオブジェクトです。

--------------------

このインターフェイスは [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) と [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTileFlip()](#getTileFlip--) | グラデーションのフリップモードを返します。 |
| [getGradientDirection()](#getGradientDirection--) | グラデーションのスタイルを返します。 |
| [getLinearGradientAngle()](#getLinearGradientAngle--) | グラデーションの角度を返します。 |
| [getLinearGradientScaled()](#getLinearGradientScaled--) | グラデーションがスケーリングされているかどうかを判定します。 |
| [getGradientShape()](#getGradientShape--) | グラデーションの形状を返します。 |
| [getGradientStops()](#getGradientStops--) | グラデーションストップのコレクションを返します。 |
### getTileFlip() {#getTileFlip--}
```
public abstract int getTileFlip()
```

グラデーションのフリップモードを返します。 読み取り専用 [TileFlip](../../com.aspose.slides/tileflip)。

**Returns:**
int
### getGradientDirection() {#getGradientDirection--}
```
public abstract int getGradientDirection()
```

グラデーションのスタイルを返します。 読み取り専用 [GradientDirection](../../com.aspose.slides/gradientdirection)。

**Returns:**
int
### getLinearGradientAngle() {#getLinearGradientAngle--}
```
public abstract float getLinearGradientAngle()
```

グラデーションの角度を返します。 読み取り専用 float。

**Returns:**
float
### getLinearGradientScaled() {#getLinearGradientScaled--}
```
public abstract boolean getLinearGradientScaled()
```

グラデーションがスケーリングされているかどうかを判定します。 読み取り専用 boolean。

**Returns:**
boolean
### getGradientShape() {#getGradientShape--}
```
public abstract byte getGradientShape()
```

グラデーションの形状を返します。 読み取り専用 [GradientShape](../../com.aspose.slides/gradientshape)。

**Returns:**
byte
### getGradientStops() {#getGradientStops--}
```
public abstract IGradientStopCollectionEffectiveData getGradientStops()
```

グラデーションストップのコレクションを返します。 読み取り専用 [IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)。

**Returns:**
[IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
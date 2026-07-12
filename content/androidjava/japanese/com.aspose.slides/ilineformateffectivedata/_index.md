---
title: ILineFormatEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 効果的なライン書式プロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ilineformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

効果的なライン書式プロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [ILineFormat](../../com.aspose.slides/ilineformat) インターフェイスと組み合わせて使用され、継承が適用された効果的な書式値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | ラインの塗りつぶし書式を返します。 |
| [getSketchFormat()](#getSketchFormat--) | ラインのスケッチ書式を返します。 |
| [getWidth()](#getWidth--) | ラインの幅を返します。 |
| [getDashStyle()](#getDashStyle--) | ラインの破線スタイルを返します。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | カスタム破線パターンを返します。 |
| [getCapStyle()](#getCapStyle--) | ラインの端点スタイルを返します。 |
| [getStyle()](#getStyle--) | ラインのスタイルを返します。 |
| [getAlignment()](#getAlignment--) | ラインの配置を返します。 |
| [getJoinStyle()](#getJoinStyle--) | ラインの結合スタイルを返します。 |
| [getMiterLimit()](#getMiterLimit--) | ラインのミタ制限を返します。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | ラインの開始位置の矢印ヘッドスタイルを返します。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | ラインの終了位置の矢印ヘッドスタイルを返します。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | ラインの開始位置の矢印ヘッド幅を返します。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | ラインの終了位置の矢印ヘッド幅を返します。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | ラインの開始位置の矢印ヘッド長さを返します。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | ラインの終了位置の矢印ヘッド長さを返します。 |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | 2 つの ILineFormatEffectiveData インスタンスが等しいかどうかを判定します。 |
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```


ラインの塗りつぶし書式を返します。 読み取り専用 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)。

**戻り値:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```


ラインのスケッチ書式を返します。 読み取り専用 [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)。

**戻り値:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


ラインの幅を返します。 読み取り専用 double。

**戻り値:**
double
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```


ラインの破線スタイルを返します。 読み取り専用 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**戻り値:**
byte
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```


カスタム破線パターンを返します。 読み取り専用 float[]。

**戻り値:**
float[]
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```


ラインの端点スタイルを返します。 読み取り専用 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**戻り値:**
byte
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```


ラインのスタイルを返します。 読み取り専用 [LineStyle](../../com.aspose.slides/linestyle)。

**戻り値:**
byte
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```


ラインの配置を返します。 読み取り専用 [LineAlignment](../../com.aspose.slides/linealignment)。

**戻り値:**
byte
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```


ラインの結合スタイルを返します。 読み取り専用 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**戻り値:**
byte
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```


ラインのミタ制限を返します。 読み取り専用 float。

**戻り値:**
float
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```


ラインの開始位置の矢印ヘッドスタイルを返します。 読み取り専用 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```


ラインの終了位置の矢印ヘッドスタイルを返します。 読み取り専用 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```


ラインの開始位置の矢印ヘッド幅を返します。 読み取り専用 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```


ラインの終了位置の矢印ヘッド幅を返します。 読み取り専用 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```


ラインの開始位置の矢印ヘッド長さを返します。 読み取り専用 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```


ラインの終了位置の矢印ヘッド長さを返します。 読み取り専用 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte
### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```


2 つの ILineFormatEffectiveData インスタンスが等しいかどうかを判定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | 現在の ILineFormatEffectiveData と比較する ILineFormatEffectiveData。 |

**戻り値:**
boolean - **true** 指定された ILineFormatEffectiveData が現在の ILineFormatEffectiveData と等しい場合; それ以外の場合は **false**。
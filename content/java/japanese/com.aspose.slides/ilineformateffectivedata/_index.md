---
title: ILineFormatEffectiveData
second_title: Aspose.Slides の Java API リファレンス
description: 効果的な線書式設定プロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ilineformateffectivedata/
---
**実装されたすべてのインターフェイス:**  
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormatEffectiveData extends ILineParamSource
```

効果的な線の書式設定プロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは、[ILineFormat](../../com.aspose.slides/ilineformat) インターフェイスと組み合わせて使用され、継承が適用された効果的な書式設定値を返します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 線の塗りつぶし形式を返します。 |
| [getSketchFormat()](#getSketchFormat--) | 線のスケッチ形式を返します。 |
| [getWidth()](#getWidth--) | 線の幅を返します。 |
| [getDashStyle()](#getDashStyle--) | 線の破線スタイルを返します。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | カスタム破線パターンを返します。 |
| [getCapStyle()](#getCapStyle--) | 線のキャップスタイルを返します。 |
| [getStyle()](#getStyle--) | 線のスタイルを返します。 |
| [getAlignment()](#getAlignment--) | 線の配置を返します。 |
| [getJoinStyle()](#getJoinStyle--) | 線の結合スタイルを返します。 |
| [getMiterLimit()](#getMiterLimit--) | 線のマイターリミットを返します。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 線の開始点にある矢じりスタイルを返します。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 線の終点にある矢じりスタイルを返します。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 線の開始点にある矢じりの幅を返します。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 線の終点にある矢じりの幅を返します。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 線の開始点にある矢じりの長さを返します。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 線の終点にある矢じりの長さを返します。 |
| [equals(ILineFormatEffectiveData lf)](#equals-com.aspose.slides.ILineFormatEffectiveData-) | 2つの ILineFormatEffectiveData インスタンスが等しいかどうかを判断します。 |

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormatEffectiveData getFillFormat()
```

線の塗りつぶし形式を返します。読み取り専用 [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)。

**戻り値:**
[ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormatEffectiveData getSketchFormat()
```

線のスケッチ形式を返します。読み取り専用 [ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)。

**戻り値:**
[ISketchFormatEffectiveData](../../com.aspose.slides/isketchformateffectivedata)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

線の幅を返します。読み取り専用 double。

**戻り値:**
double

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

線の破線スタイルを返します。読み取り専用 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**戻り値:**
byte

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

カスタム破線パターンを返します。読み取り専用 float[]。

**戻り値:**
float[]

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

線のキャップスタイルを返します。読み取り専用 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**戻り値:**
byte

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

線のスタイルを返します。読み取り専用 [LineStyle](../../com.aspose.slides/linestyle)。

**戻り値:**
byte

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

線の配置を返します。読み取り専用 [LineAlignment](../../com.aspose.slides/linealignment)。

**戻り値:**
byte

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

線の結合スタイルを返します。読み取り専用 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**戻り値:**
byte

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

線のマイターリミットを返します。読み取り専用 float。

**戻り値:**
float

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

線の開始点にある矢じりスタイルを返します。読み取り専用 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

線の終点にある矢じりスタイルを返します。読み取り専用 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

線の開始点にある矢じりの幅を返します。読み取り専用 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

線の終点にある矢じりの幅を返します。読み取り専用 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

線の開始点にある矢じりの長さを返します。読み取り専用 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

線の終点にある矢じりの長さを返します。読み取り専用 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte

### equals(ILineFormatEffectiveData lf) {#equals-com.aspose.slides.ILineFormatEffectiveData-}
```
public abstract boolean equals(ILineFormatEffectiveData lf)
```

2つの ILineFormatEffectiveData インスタンスが等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lf | [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) | 現在の ILineFormatEffectiveData と比較する ILineFormatEffectiveData。 |

**戻り値:**
boolean - **true** の場合、指定された ILineFormatEffectiveData が現在の ILineFormatEffectiveData と等しいことを示します。それ以外の場合は **false**。
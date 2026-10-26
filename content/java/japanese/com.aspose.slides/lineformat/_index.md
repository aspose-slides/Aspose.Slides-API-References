---
title: LineFormat
second_title: Aspose.Slides for Java API リファレンス
description: 行の書式を表します。
type: docs
url: /ja/com.aspose.slides/lineformat/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

行の書式を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | ラインの書式が未定義の場合に true を返します（作成直後、デフォルト）。 |
| [getFillFormat()](#getFillFormat--) | ラインの塗りつぶし書式を返します。 |
| [getSketchFormat()](#getSketchFormat--) | ラインのスケッチ書式を返します。 |
| [getWidth()](#getWidth--) | ラインの幅を取得または設定します。 |
| [setWidth(double value)](#setWidth-double-) | ラインの幅を取得または設定します。 |
| [getDashStyle()](#getDashStyle--) | ラインの破線スタイルを取得または設定します。 |
| [setDashStyle(byte value)](#setDashStyle-byte-) | ラインの破線スタイルを取得または設定します。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | カスタム破線パターンを取得または設定します。 |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | カスタム破線パターンを取得または設定します。 |
| [getCapStyle()](#getCapStyle--) | ラインの端スタイルを取得または設定します。 |
| [setCapStyle(byte value)](#setCapStyle-byte-) | ラインの端スタイルを取得または設定します。 |
| [getStyle()](#getStyle--) | ラインのスタイルを取得または設定します。 |
| [setStyle(byte value)](#setStyle-byte-) | ラインのスタイルを取得または設定します。 |
| [getAlignment()](#getAlignment--) | ラインの配置を取得または設定します。 |
| [setAlignment(byte value)](#setAlignment-byte-) | ラインの配置を取得または設定します。 |
| [getJoinStyle()](#getJoinStyle--) | ラインの結合スタイルを取得または設定します。 |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | ラインの結合スタイルを取得または設定します。 |
| [getMiterLimit()](#getMiterLimit--) | ラインの斜め継ぎ限界を取得または設定します。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | ラインの斜め継ぎ限界を取得または設定します。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | ラインの開始側の矢じりスタイルを取得または設定します。 |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | ラインの開始側の矢じりスタイルを取得または設定します。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | ラインの終了側の矢じりスタイルを取得または設定します。 |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | ラインの終了側の矢じりスタイルを取得または設定します。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | ラインの開始側の矢じりの幅を取得または設定します。 |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | ラインの開始側の矢じりの幅を取得または設定します。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | ラインの終了側の矢じりの幅を取得または設定します。 |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | ラインの終了側の矢じりの幅を取得または設定します。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | ラインの開始側の矢じりの長さを取得または設定します。 |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | ラインの開始側の矢じりの長さを取得または設定します。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | ラインの終了側の矢じりの長さを取得または設定します。 |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | ラインの終了側の矢じりの長さを取得または設定します。 |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | 2つの LineFormat インスタンスが等しいかどうかを判断します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なライン書式データを取得します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定されたオブジェクトと比較します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**戻り値:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```

ラインの書式が未定義の場合に true を返します（作成直後、デフォルト）。読み取り専用 boolean 。

**戻り値:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

ラインの塗りつぶし書式を返します。読み取り専用 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**戻り値:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

ラインのスケッチ書式を返します。読み取り専用 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**戻り値:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```

ラインの幅を取得または設定します。読み書き可能 double 。

**戻り値:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

ラインの幅を取得または設定します。読み書き可能 double 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

ラインの破線スタイルを取得または設定します。読み書き可能 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**戻り値:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

ラインの破線スタイルを取得または設定します。読み書き可能 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

カスタム破線パターンを取得または設定します。読み書き可能 float[] 。

**戻り値:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

カスタム破線パターンを取得または設定します。読み書き可能 float[] 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

ラインの端スタイルを取得または設定します。読み書き可能 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**戻り値:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

ラインの端スタイルを取得または設定します。読み書き可能 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```

ラインのスタイルを取得または設定します。読み書き可能 [LineStyle](../../com.aspose.slides/linestyle)。

**戻り値:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

ラインのスタイルを取得または設定します。読み書き可能 [LineStyle](../../com.aspose.slides/linestyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

ラインの配置を取得または設定します。読み書き可能 [LineAlignment](../../com.aspose.slides/linealignment)。

**戻り値:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

ラインの配置を取得または設定します。読み書き可能 [LineAlignment](../../com.aspose.slides/linealignment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

ラインの結合スタイルを取得または設定します。読み書き可能 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**戻り値:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

ラインの結合スタイルを取得または設定します。読み書き可能 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

ラインの斜め継ぎ限界を取得または設定します。読み書き可能 float 。

**戻り値:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

ラインの斜め継ぎ限界を取得または設定します。読み書き可能 float 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

ラインの開始側の矢じりスタイルを取得または設定します。読み書き可能 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

ラインの開始側の矢じりスタイルを取得または設定します。読み書き可能 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

ラインの終了側の矢じりスタイルを取得または設定します。読み書き可能 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

ラインの終了側の矢じりスタイルを取得または設定します。読み書き可能 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

ラインの開始側の矢じりの幅を取得または設定します。読み書き可能 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

ラインの開始側の矢じりの幅を取得または設定します。読み書き可能 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

ラインの終了側の矢じりの幅を取得または設定します。読み書き可能 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

ラインの終了側の矢じりの幅を取得または設定します。読み書き可能 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

ラインの開始側の矢じりの長さを取得または設定します。読み書き可能 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

ラインの開始側の矢じりの長さを取得または設定します。読み書き可能 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

ラインの終了側の矢じりの長さを取得または設定します。読み書き可能 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

ラインの終了側の矢じりの長さを取得または設定します。読み書き可能 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

2つの LineFormat インスタンスが等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 現在の LineFormat と比較する LineFormat。 |

**戻り値:**
boolean - **true**（指定された LineFormat が現在の LineFormat と等しい場合）。それ以外は **false**。
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

継承が適用された有効なライン書式データを取得します。

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) のインスタンス。
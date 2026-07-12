---
title: LineFormat
second_title: Java APIリファレンスによる Android 用 Aspose.Slides
description: 線の書式を表します。
type: docs
url: /ja/com.aspose.slides/lineformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)  
```
public final class LineFormat extends PVIObject implements ILineFormat
```

線の書式を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | ライン書式が未定義の場合に true を返します（作成直後、デフォルト）。 |
| [getFillFormat()](#getFillFormat--) | 線の塗りつぶし書式を返します。 |
| [getSketchFormat()](#getSketchFormat--) | 線のスケッチ書式を返します。 |
| [getWidth()](#getWidth--) | 線の幅を取得または設定します。 |
| [setWidth(double value)](#setWidth-double-) | 線の幅を取得または設定します。 |
| [getDashStyle()](#getDashStyle--) | 線の破線スタイルを取得または設定します。 |
| [setDashStyle(byte value)](#setDashStyle-byte-) | 線の破線スタイルを取得または設定します。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | カスタム破線パターンを取得または設定します。 |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | カスタム破線パターンを取得または設定します。 |
| [getCapStyle()](#getCapStyle--) | 線のキャップスタイルを取得または設定します。 |
| [setCapStyle(byte value)](#setCapStyle-byte-) | 線のキャップスタイルを取得または設定します。 |
| [getStyle()](#getStyle--) | 線のスタイルを取得または設定します。 |
| [setStyle(byte value)](#setStyle-byte-) | 線のスタイルを取得または設定します。 |
| [getAlignment()](#getAlignment--) | 線の配置を取得または設定します。 |
| [setAlignment(byte value)](#setAlignment-byte-) | 線の配置を取得または設定します。 |
| [getJoinStyle()](#getJoinStyle--) | 線の結合スタイルを取得または設定します。 |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | 線の結合スタイルを取得または設定します。 |
| [getMiterLimit()](#getMiterLimit--) | 線のミータリミットを取得または設定します。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 線のミータリミットを取得または設定します。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | 線の開始点における矢じりスタイルを取得または設定します。 |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | 線の開始点における矢じりスタイルを取得または設定します。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | 線の終点における矢じりスタイルを取得または設定します。 |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | 線の終点における矢じりスタイルを取得または設定します。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | 線の開始点における矢じりの幅を取得または設定します。 |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | 線の開始点における矢じりの幅を取得または設定します。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | 線の終点における矢じりの幅を取得または設定します。 |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | 線の終点における矢じりの幅を取得または設定します。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | 線の開始点における矢じりの長さを取得または設定します。 |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | 線の開始点における矢じりの長さを取得または設定します。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | 線の終点における矢じりの長さを取得または設定します。 |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | 線の終点における矢じりの長さを取得または設定します。 |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | 2つの LineFormat インスタンスが等しいかどうかを判定します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効な線書式データを取得します。 |

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

ライン書式が未定義の場合に true を返します（作成直後、デフォルト）。読み取り専用 boolean 。

**戻り値:**
boolean

### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```

線の塗りつぶし書式を返します。読み取り専用 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**戻り値:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```

線のスケッチ書式を返します。読み取り専用 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**戻り値:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public final double getWidth()
```

線の幅を取得または設定します。読み書き  double .

**戻り値:**
double

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

線の幅を取得または設定します。読み書き  double .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```

線の破線スタイルを取得または設定します。読み書き [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**戻り値:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```

線の破線スタイルを取得または設定します。読み書き [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```

カスタム破線パターンを取得または設定します。読み書き  float[] .

**戻り値:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```

カスタム破線パターンを取得または設定します。読み書き  float[] .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```

線のキャップスタイルを取得または設定します。読み書き [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**戻り値:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```

線のキャップスタイルを取得または設定します。読み書き [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public final byte getStyle()
```

線のスタイルを取得または設定します。読み書き [LineStyle](../../com.aspose.slides/linestyle)。

**戻り値:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```

線のスタイルを取得または設定します。読み書き [LineStyle](../../com.aspose.slides/linestyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```

線の配置を取得または設定します。読み書き [LineAlignment](../../com.aspose.slides/linealignment)。

**戻り値:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```

線の配置を取得または設定します。読み書き [LineAlignment](../../com.aspose.slides/linealignment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```

線の結合スタイルを取得または設定します。読み書き [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**戻り値:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```

線の結合スタイルを取得または設定します。読み書き [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```

線のミータリミットを取得または設定します。読み書き  float .

**戻り値:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```

線のミータリミットを取得または設定します。読み書き  float .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```

線の開始点における矢じりスタイルを取得または設定します。読み書き [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```

線の開始点における矢じりスタイルを取得または設定します。読み書き [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```

線の終点における矢じりスタイルを取得または設定します。読み書き [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```

線の終点における矢じりスタイルを取得または設定します。読み書き [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```

線の開始点における矢じりの幅を取得または設定します。読み書き [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```

線の開始点における矢じりの幅を取得または設定します。読み書き [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```

線の終点における矢じりの幅を取得または設定します。読み書き [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```

線の終点における矢じりの幅を取得または設定します。読み書き [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```

線の開始点における矢じりの長さを取得または設定します。読み書き [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```

線の開始点における矢じりの長さを取得または設定します。読み書き [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```

線の終点における矢じりの長さを取得または設定します。読み書き [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```

線の終点における矢じりの長さを取得または設定します。読み書き [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```

2つの LineFormat インスタンスが等しいかどうかを判定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 現在の LineFormat と比較する LineFormat。 |

**戻り値:**
boolean - 指定された LineFormat が現在の LineFormat と等しい場合は **true**、それ以外の場合は **false**。

### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```

継承が適用された有効な線書式データを取得します。

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
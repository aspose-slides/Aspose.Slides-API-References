---
title: ILineFormat
second_title: Aspose.Slides for Android の Java API リファレンス
description: ラインの書式を表します。
type: docs
url: /ja/com.aspose.slides/ilineformat/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

ラインの書式を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | ライン フォーマットが未定義（作成直後のデフォルト）の場合は true を返します。 |
| [getFillFormat()](#getFillFormat--) | ラインの塗りつぶし書式を返します。 |
| [getSketchFormat()](#getSketchFormat--) | ラインのスケッチ書式を返します。 |
| [getWidth()](#getWidth--) | ラインの幅を取得または設定します。 |
| [setWidth(double value)](#setWidth-double-) | ラインの幅を取得または設定します。 |
| [getDashStyle()](#getDashStyle--) | ラインの破線スタイルを取得または設定します。 |
| [setDashStyle(byte value)](#setDashStyle-byte-) | ラインの破線スタイルを取得または設定します。 |
| [getCustomDashPattern()](#getCustomDashPattern--) | カスタム破線パターンを取得または設定します。 |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | カスタム破線パターンを取得または設定します。 |
| [getCapStyle()](#getCapStyle--) | ラインの端キャップスタイルを取得または設定します。 |
| [setCapStyle(byte value)](#setCapStyle-byte-) | ラインの端キャップスタイルを取得または設定します。 |
| [getStyle()](#getStyle--) | ラインのスタイルを取得または設定します。 |
| [setStyle(byte value)](#setStyle-byte-) | ラインのスタイルを取得または設定します。 |
| [getAlignment()](#getAlignment--) | ラインの配置を取得または設定します。 |
| [setAlignment(byte value)](#setAlignment-byte-) | ラインの配置を取得または設定します。 |
| [getJoinStyle()](#getJoinStyle--) | ラインの結合スタイルを取得または設定します。 |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | ラインの結合スタイルを取得または設定します。 |
| [getMiterLimit()](#getMiterLimit--) | ラインのマイタ限界値を取得または設定します。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | ラインのマイタ限界値を取得または設定します。 |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | ラインの開始位置にある矢じりスタイルを取得または設定します。 |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | ラインの開始位置にある矢じりスタイルを取得または設定します。 |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | ラインの終了位置にある矢じりスタイルを取得または設定します。 |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | ラインの終了位置にある矢じりスタイルを取得または設定します。 |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | ラインの開始位置にある矢じりの幅を取得または設定します。 |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | ラインの開始位置にある矢じりの幅を取得または設定します。 |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | ラインの終了位置にある矢じりの幅を取得または設定します。 |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | ラインの終了位置にある矢じりの幅を取得または設定します。 |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | ラインの開始位置にある矢じりの長さを取得または設定します。 |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | ラインの開始位置にある矢じりの長さを取得または設定します。 |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | ラインの終了位置にある矢じりの長さを取得または設定します。 |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | ラインの終了位置にある矢じりの長さを取得または設定します。 |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | 2 つの LineFormat インスタンスが等しいかどうかを判断します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なライン書式データを取得します。 |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

ライン フォーマットが未定義（作成直後のデフォルト）の場合は true を返します。読み取り専用 boolean。

**戻り値:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

ラインの塗りつぶし書式を返します。読み取り専用 [ILineFillFormat](../../com.aspose.slides/ilinefillformat)。

**戻り値:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

ラインのスケッチ書式を返します。読み取り専用 [ISketchFormat](../../com.aspose.slides/isketchformat)。

**戻り値:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

ラインの幅を取得または設定します。読み書き可能 double。

**戻り値:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

ラインの幅を取得または設定します。読み書き可能 double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

ラインの破線スタイルを取得または設定します。読み書き可能 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**戻り値:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

ラインの破線スタイルを取得または設定します。読み書き可能 [LineDashStyle](../../com.aspose.slides/linedashstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

カスタム破線パターンを取得または設定します。読み書き可能 float[]。

**戻り値:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

カスタム破線パターンを取得または設定します。読み書き可能 float[]。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

ラインの端キャップスタイルを取得または設定します。読み書き可能 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**戻り値:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

ラインの端キャップスタイルを取得または設定します。読み書き可能 [LineCapStyle](../../com.aspose.slides/linecapstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

ラインのスタイルを取得または設定します。読み書き可能 [LineStyle](../../com.aspose.slides/linestyle)。

**戻り値:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

ラインのスタイルを取得または設定します。読み書き可能 [LineStyle](../../com.aspose.slides/linestyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

ラインの配置を取得または設定します。読み書き可能 [LineAlignment](../../com.aspose.slides/linealignment)。

**戻り値:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

ラインの配置を取得または設定します。読み書き可能 [LineAlignment](../../com.aspose.slides/linealignment)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

ラインの結合スタイルを取得または設定します。読み書き可能 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**戻り値:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

ラインの結合スタイルを取得または設定します。読み書き可能 [LineJoinStyle](../../com.aspose.slides/linejoinstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

ラインのマイタ限界値を取得または設定します。読み書き可能 float。

**戻り値:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

ラインのマイタ限界値を取得または設定します。読み書き可能 float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

ラインの開始位置にある矢じりスタイルを取得または設定します。読み書き可能 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

ラインの開始位置にある矢じりスタイルを取得または設定します。読み書き可能 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

ラインの終了位置にある矢じりスタイルを取得または設定します。読み書き可能 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**戻り値:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

ラインの終了位置にある矢じりスタイルを取得または設定します。読み書き可能 [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

ラインの開始位置にある矢じりの幅を取得または設定します。読み書き可能 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

ラインの開始位置にある矢じりの幅を取得または設定します。読み書き可能 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

ラインの終了位置にある矢じりの幅を取得または設定します。読み書き可能 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**戻り値:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

ラインの終了位置にある矢じりの幅を取得または設定します。読み書き可能 [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

ラインの開始位置にある矢じりの長さを取得または設定します。読み書き可能 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

ラインの開始位置にある矢じりの長さを取得または設定します。読み書き可能 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

ラインの終了位置にある矢じりの長さを取得または設定します。読み書き可能 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**戻り値:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

ラインの終了位置にある矢じりの長さを取得または設定します。読み書き可能 [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

2 つの LineFormat インスタンスが等しいかどうかを判断します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | 現在の LineFormat と比較する LineFormat。 |

**戻り値:**
boolean - **true** の場合、指定された LineFormat が現在の LineFormat と等しいことを示します。それ以外の場合は **false**。

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

継承が適用された有効なライン書式データを取得します。

**戻り値:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - 1つの [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)。
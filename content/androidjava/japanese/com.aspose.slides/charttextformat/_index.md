---
title: ChartTextFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: チャートのテキスト要素のデフォルトテキスト書式を指定します。
type: docs
url: /ja/com.aspose.slides/charttextformat/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject  
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

チャートのテキスト要素のデフォルトのテキスト書式を指定します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copies text format to specified text frame. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copies text format from specified text frame. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```

TextBlockFormat. 読み取り専用 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**戻り値:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```

ParagraphFormat. 読み取り専用 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**戻り値:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)

### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```

PortionFormat. 読み取り専用 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**戻り値:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)

### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```

指定されたテキストフレームにテキスト書式をコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | テキスト書式をコピーする対象のテキストフレーム。 |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```

指定されたテキストフレームからテキスト書式をコピーします。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | テキスト書式をコピー元のテキストフレーム。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
---
title: Column
second_title: Java API リファレンス – Android 用 Aspose.Slides
description: テーブル内の列を表します。
type: docs
url: /ja/com.aspose.slides/column/
---
**継承:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

テーブル内の列を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | 列の幅を取得または設定します。 |
| [setWidth(double value)](#setWidth-double-) | 列の幅を取得または設定します。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 列のセルのすべての部分に定義された部分フォーマット プロパティを設定します。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 列のセルのすべての段落に定義された段落フォーマット プロパティを設定します。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 列のセルのすべてのテキストフレームに定義されたテキストフレーム フォーマット プロパティを設定します。 |
| [getColumnFormat()](#getColumnFormat--) | この列のフォーマット プロパティを含む ColumnFormat オブジェクトを取得します。 |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

列の幅を取得または設定します。読み書き可能な double 型。

**戻り値:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

列の幅を取得または設定します。読み書き可能な double 型。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

列のセルのすべての部分に定義された部分フォーマット プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 必要なプロパティが設定された IPortionFormat オブジェクト。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

列のセルのすべての段落に定義された段落フォーマット プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 必要なプロパティが設定された IParagraphFormat オブジェクト。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

列のセルのすべてのテキストフレームに定義されたテキストフレーム フォーマット プロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 必要なプロパティが設定された ITextFrameFormat オブジェクト。 |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

この列のフォーマット プロパティを含む ColumnFormat オブジェクトを取得します。読み取り専用 [IColumnFormat](../../com.aspose.slides/icolumnformat)。

**戻り値:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
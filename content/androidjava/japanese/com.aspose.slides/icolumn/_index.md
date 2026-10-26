---
title: IColumn
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テーブル内の列を表します。
type: docs
url: /ja/com.aspose.slides/icolumn/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)  
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

テーブルの列を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | 列の幅を取得または設定します。 |
| [setWidth(double value)](#setWidth-double-) | 列の幅を取得または設定します。 |
| [getColumnFormat()](#getColumnFormat--) | この列の書式設定プロパティを含む ColumnFormat オブジェクトを取得します。 |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

列の幅を取得または設定します。 読み書き可能 double.

**戻り値:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

列の幅を取得または設定します。 読み書き可能 double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

この列の書式設定プロパティを含む ColumnFormat オブジェクトを取得します。 読み取り専用 [IColumnFormat](../../com.aspose.slides/icolumnformat)。

**戻り値:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
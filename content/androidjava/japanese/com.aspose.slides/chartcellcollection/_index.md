---
title: ChartCellCollection
second_title: Aspose.Slides for Android の Java API リファレンス
description: データを含むセルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/chartcellcollection/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

データを含むセルのコレクションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | ワークブック内のセルセットのアドレスを返します。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | すべてのセルの文字列値を連結した文字列を取得します。 |
| [get_Item(int index)](#get-Item-int-) | インデックスでセル (IChartDataCell) を返します。 |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | コレクションに新しいセルを追加します。 |
| [add(Object value)](#add-java.lang.Object-) | 指定された値から [ChartDataCell](../../com.aspose.slides/chartdatacell) を作成し、コレクションに追加します。 |
| [removeAt(int index)](#removeAt-int-) | インデックスでコレクションからセルを削除します。 |
| [getCount()](#getCount--) | コレクション内のセル数を取得します。 |
| [iterator()](#iterator--) | コレクションを反復処理する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の java イテレータを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

ワークブック内のセルセットのアドレスを返します。

**戻り値:**
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

すべてのセルの文字列値を連結した文字列を取得します。

**戻り値:**
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

インデックスでセル (IChartDataCell) を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | セルのインデックス。 |

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - データを持つセル。

### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

コレクションに新しいセルを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 追加する新しいセル。 |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

指定された値から [ChartDataCell](../../com.aspose.slides/chartdatacell) を作成し、コレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object | 値。

--------------------

このメソッドは名前が AUTO_DATA のワークシートを追加し、すべての値をそこに追加します。[ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないでください。このメソッドで追加できる最大値の数は 16711680 を超えてはなりません |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

インデックスでコレクションからセルを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するセルのインデックス。 |

### getCount() {#getCount--}
```
public final int getCount()
```

コレクション内のセル数を取得します。読み取り専用 int。

**戻り値:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

コレクションを反復処理する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - コレクションを反復処理できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

コレクション全体の java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - コレクション全体の java.util.Iterator。

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
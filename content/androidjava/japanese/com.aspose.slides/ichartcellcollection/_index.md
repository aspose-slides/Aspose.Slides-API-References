---
title: IChartCellCollection
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: データを持つセルのコレクションを表します。
type: docs
url: /ja/com.aspose.slides/ichartcellcollection/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

データを持つセルのコレクションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | ワークブック内のセルセットのアドレスを返します。 |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | すべてのセルの文字列値を連結した文字列です。 |
| [get_Item(int index)](#get-Item-int-) | インデックスでセル (IChartDataCell) を返します。 |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | コレクションに新しいセルを追加します。 |
| [add(Object value)](#add-java.lang.Object-) | 指定された値から [IChartDataCell](../../com.aspose.slides/ichartdatacell) を作成し、コレクションに追加します。 |
| [removeAt(int index)](#removeAt-int-) | インデックスでコレクションからセルを削除します。 |
| [getCount()](#getCount--) | コレクション内のセル数を取得します。 |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


ワークブック内のセルセットのアドレスを返します。

**返り値:**
java.lang.String - ワークブック内のセルセットのアドレス String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


すべてのセルの文字列値を連結した文字列です。

**返り値:**
java.lang.String - 結果の文字列 String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


インデックスでセル (IChartDataCell) を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | セルのインデックス。 |

**返り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - データを持つセル。
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```


コレクションに新しいセルを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 追加する新しいセル。 |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


指定された値から [IChartDataCell](../../com.aspose.slides/ichartdatacell) を作成し、コレクションに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object | その値。

--------------------

このメソッドは AUTO_DATA という名前のワークシートを追加し、すべての値をそこに追加します。[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) を使用してセルの値を追加または編集する場合は、このワークシートを使用しないようにしてください。このメソッドで追加できる値の最大数は 16711680 を超えてはなりません |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


インデックスでコレクションからセルを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するセルのインデックス。 |

### getCount() {#getCount--}
```
public abstract int getCount()
```


コレクション内のセル数を取得します。読み取り専用 int。

**返り値:**
int
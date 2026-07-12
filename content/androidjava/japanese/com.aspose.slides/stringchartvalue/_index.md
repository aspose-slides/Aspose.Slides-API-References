---
title: StringChartValue
second_title: Java API リファレンスによる Android 向け Aspose.Slides
description: pptx プレゼンテーション ドキュメントに保存できる文字列値を、1) チャートに関連するワークブックのセル/セル群に格納する方法、2) リテラル値として格納する方法の 2 つの方式で表します。
type: docs
url: /ja/com.aspose.slides/stringchartvalue/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

pptx プレゼンテーション ドキュメントに保存できる文字列値を 2 つの方法で表します。1) チャートに関連付けられたワークブックのセル/セル群に格納する方法、2) リテラル値として格納する方法。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAsCells()](#getAsCells--) | null 値の代入は許可されていません。 |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | null 値の代入は許可されていません。 |
| [getAsLiteralString()](#getAsLiteralString--) | リテラル文字列として値を取得または設定します。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | リテラル文字列として値を取得または設定します。 |
| [getData()](#getData--) | Data オブジェクトを取得または設定します。 |
| [setData(Object value)](#setData-java.lang.Object-) | Data オブジェクトを取得または設定します。 |
| [toString()](#toString--) | 文字列値データを返します。 |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 指定されたセルから値を設定します。 |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | DataSourceType プロパティが DataSourceType.Worksheet の場合、このメソッドは文字列データを表すワークブック内のセルのアドレスを返します。 |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

null 値の代入は許可されていません。返される値は常に null ではありません。Read/write [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**戻り値:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

null 値の代入は許可されていません。返される値は常に null ではありません。Read/write [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

リテラル文字列として値を取得または設定します。Read/write String。

**戻り値:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

リテラル文字列として値を取得または設定します。Read/write String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Data オブジェクトを取得または設定します。Read/write Object。

**戻り値:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Data オブジェクトを取得または設定します。Read/write Object。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

文字列値データを返します。DataSourceType が false で文字列値が割り当てられていない場合は null を返します。

**戻り値:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

指定されたセルから値を設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | セル。 |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

DataSourceType プロパティが DataSourceType.Worksheet の場合、このメソッドは文字列データを表すワークブック内のセルのアドレスを返します。それ以外の場合は空文字列を返します。

**戻り値:**
java.lang.String
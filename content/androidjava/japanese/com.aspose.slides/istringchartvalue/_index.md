---
title: IStringChartValue
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: pptx プレゼンテーション ドキュメントに格納できる文字列値を、2 つの方法で表現します。1) チャートに関連付けられたワークブックのセル/セル群に格納する方法、2) リテラル値として格納する方法。
type: docs
url: /ja/com.aspose.slides/istringchartvalue/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

pptx プレゼンテーション ドキュメントに格納できる文字列値を、次の 2 つの方法で表現します：1) チャートに関連付けられたワークブックのセル/セル群に格納する方法；2) リテラル値として格納する方法。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。 |
| [toString()](#toString--) | 文字列表現を取得します。 |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | 指定されたセルから値を設定します。 |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | DataSourceType プロパティが DataSourceType.Worksheet の場合、このメソッドは文字列データを表すブック内のセルのアドレスを返します。 |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。読み書き可能な String。

**戻り値:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。読み書き可能な String。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

文字列表現を取得します。

**戻り値:**
java.lang.String - 値の String 表現

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

指定されたセルから値を設定します。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | セル。 |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

DataSourceType プロパティが DataSourceType.Worksheet の場合、このメソッドは文字列データを表すブック内のセルのアドレスを返します。そうでない場合は空文字列を返します。

**戻り値:**
java.lang.String - String 値
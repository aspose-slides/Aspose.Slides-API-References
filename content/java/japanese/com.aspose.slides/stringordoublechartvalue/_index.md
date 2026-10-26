---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for Java API リファレンス
description: pptx プレゼンテーション ドキュメントに保存できる文字列または double 値を、次の 2 つの方法で表します：1) チャートに関連付けられたブックのセル/セル群に格納する方法、2) リテラル値として格納する方法。
type: docs
url: /ja/com.aspose.slides/stringordoublechartvalue/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

PPTX プレゼンテーション ドキュメントに保存できる文字列または double 値を表します。保存方法は 2 つあります：1) チャートに関連付けられたブックのセル/セル群に格納する方法；2) リテラル値として格納する方法。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAsCell()](#getAsCell--) | Returns or sets chart data cell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets chart data cell. |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets value as literal string. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets value as literal string. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Returns or sets value as literal double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Returns or sets value as literal double. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toDouble()](#toDouble--) | Converts to double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

チャートデータセルを取得または設定します。読み書き [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

チャートデータセルを取得または設定します。読み書き [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

リテラル文字列としての値を取得または設定します。読み書き String。

**戻り値:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

リテラル文字列としての値を取得または設定します。読み書き String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

リテラル double としての値を取得または設定します。読み書き double。

**戻り値:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

リテラル double としての値を取得または設定します。読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Data オブジェクトを取得または設定します。読み書き Object。

**戻り値:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Data オブジェクトを取得または設定します。読み書き Object。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

double に変換します。

**戻り値:**
double - Double value.
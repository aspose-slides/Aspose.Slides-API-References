---
title: DoubleChartValue
second_title: Java API リファレンス（Android 用 Aspose.Slides）
description: pptx プレゼンテーション ドキュメントに保存できる double 値を、2 つの方法で表します: 1) チャートに関連付けられたワークブックのセル/セル群に格納する方法、2) リテラル値として格納する方法。
type: docs
url: /ja/com.aspose.slides/doublechartvalue/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

pptx プレゼンテーション文書に保存できる double 値を 2 つの方法で表します: 1) チャートに関連付けられたワークブックのセル/セル群に格納する方法; 2) リテラル値として格納する方法。
## メソッド

| Method | Description |
| --- | --- |
| [getAsCell()](#getAsCell--) | チャートデータセルを取得または設定します。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | チャートデータセルを取得または設定します。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | リテラル double 値を取得または設定します。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | リテラル double 値を取得または設定します。 |
| [getData()](#getData--) | Data オブジェクトを取得または設定します。 |
| [setData(Object value)](#setData-java.lang.Object-) | Data オブジェクトを取得または設定します。 |
| [toDouble()](#toDouble--) | double に変換します。 |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


チャートデータセルを取得または設定します。 読み書き [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


チャートデータセルを取得または設定します。 読み書き [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


リテラル double 値を取得または設定します。 読み書き double。

**戻り値:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


リテラル double 値を取得または設定します。 読み書き double。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Data オブジェクトを取得または設定します。 読み書き Object。

**戻り値:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Data オブジェクトを取得または設定します。 読み書き Object。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```


double に変換します。

**戻り値:**
double - DataSourceType が DoubleLiterals の場合は LiteralDouble を返します。DataSourceType が Worksheet の場合は、セルの値を double に正常に変換して返し、そうでない場合は NaN を返します。
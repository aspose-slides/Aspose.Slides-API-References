---
title: StringOrDoubleChartValue
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 文字列または倍精度浮動小数点数の値を表します。この値は pptx プレゼンテーション ドキュメントに 2 つの方法で格納できます。1) チャートに関連付けられたワークブックのセル/セル群に、2) リテラル値として。
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

文字列または倍精度浮動小数点数の値を表します。この値は pptx プレゼンテーション ドキュメントに次の 2 つの方法で格納できます: 1) チャートに関連付けられたワークブックのセル/セル群に; 2) リテラル値として。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAsCell()](#getAsCell--) | チャート データ セルを取得または設定します。 |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | チャート データ セルを取得または設定します。 |
| [getAsLiteralString()](#getAsLiteralString--) | リテラル文字列としての値を取得または設定します。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | リテラル文字列としての値を取得または設定します。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | リテラル倍精度浮動小数点数としての値を取得または設定します。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | リテラル倍精度浮動小数点数としての値を取得または設定します。 |
| [getData()](#getData--) | Data オブジェクトを取得または設定します。 |
| [setData(Object value)](#setData-java.lang.Object-) | Data オブジェクトを取得または設定します。 |
| [toDouble()](#toDouble--) | double に変換します。 |

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

チャート データ セルを取得または設定します。読み取り/書き込み [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**戻り値:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

チャート データ セルを取得または設定します。読み取り/書き込み [IChartDataCell](../../com.aspose.slides/ichartdatacell)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

リテラル文字列としての値を取得または設定します。読み取り/書き込み String。

**戻り値:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

リテラル文字列としての値を取得または設定します。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

リテラル倍精度浮動小数点数としての値を取得または設定します。読み取り/書き込み double。

**戻り値:**  
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

リテラル倍精度浮動小数点数としての値を取得または設定します。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Data オブジェクトを取得または設定します。読み取り/書き込み Object。

**戻り値:**  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Data オブジェクトを取得または設定します。読み取り/書き込み Object。

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
double - ダブル値。
---
title: IDoubleChartValue
second_title: Aspose.Slides の Java API リファレンス
description: pptx プレゼンテーション ドキュメントに保存できる double 値を、2 つの方法で表します。1) チャートに関連付けられたワークブックのセル/セル群、2) リテラル値として。
type: docs
url: /ja/com.aspose.slides/idoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

pptx プレゼンテーション ドキュメントに保存できる double 値を 2 つの方法で表します: 1) チャートに関連付けられたワークブックのセル/セル群に; 2) リテラル値として。

## Methods

| メソッド | 説明 |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType = Charts.DataSourceType.DoubleLiterals の場合、リテラル double 値を取得または設定します。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType = Charts.DataSourceType.DoubleLiterals の場合、リテラル double 値を取得または設定します。 |
| [toDouble()](#toDouble--) | double に変換します。 |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

DataSourceType = Charts.DataSourceType.DoubleLiterals の場合、リテラル double 値を取得または設定します。読み取り/書き込み double.

**戻り値:**  
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

DataSourceType = Charts.DataSourceType.DoubleLiterals の場合、リテラル double 値を取得または設定します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

double に変換します。

**戻り値:**  
double - Double 値。
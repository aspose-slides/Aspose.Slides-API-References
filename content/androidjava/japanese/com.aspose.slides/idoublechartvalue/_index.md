---
title: IDoubleChartValue
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: pptx プレゼンテーション ドキュメントに格納できる double 値を、次の 2 つの方法で表します。1) チャートに関連付けられたワークブックのセル/セル群に格納する方法、2) リテラル値として格納する方法。
type: docs
url: /ja/com.aspose.slides/idoublechartvalue/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

pptx プレゼンテーション ドキュメントに格納できる double 値を、次の 2 つの方法で表します: 1) チャートに関連付けられたワークブックのセル/セル群に; 2) リテラル値として。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType = Charts.DataSourceType.DoubleLiterals の場合、リテラル double 値を取得または設定します。 読み取り/書き込み double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType = Charts.DataSourceType.DoubleLiterals の場合、リテラル double 値を取得または設定します。 読み取り/書き込み double. |
| [toDouble()](#toDouble--) | double に変換します。 |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

DataSourceType = Charts.DataSourceType.DoubleLiterals の場合、リテラル double 値を取得または設定します。 読み取り/書き込み double.

**戻り値:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

DataSourceType = Charts.DataSourceType.DoubleLiterals の場合、リテラル double 値を取得または設定します。 読み取り/書き込み double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

double に変換します。

**戻り値:**
double - Double 値。
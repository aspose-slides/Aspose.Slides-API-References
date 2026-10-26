---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides for Android の Java API リファレンス
description: pptx プレゼンテーション ドキュメントに保存できる文字列または double 値を、次の 2 つの方法で表します。1) チャートに関連付けられたブックのセル/セル群に、2) リテラル値として。
type: docs
url: /ja/com.aspose.slides/istringordoublechartvalue/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

文字列または double 値を表し、pptx プレゼンテーション ドキュメントに次の 2 つの方法で保存できます: 1) チャートに関連付けられたブックのセル/セル群に; 2) リテラル値として。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。 |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。 |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | DataSourceType プロパティが DataSourceType.DoubleLiterals の場合、リテラル double を取得または設定します。 |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | DataSourceType プロパティが DataSourceType.DoubleLiterals の場合、リテラル double を取得または設定します。 |
| [toDouble()](#toDouble--) | 値を double に変換します。 |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。読み取り/書き込み可能な String。

**戻り値:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。読み取り/書き込み可能な String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

DataSourceType プロパティが DataSourceType.DoubleLiterals の場合、リテラル double を取得または設定します。読み取り/書き込み可能な double。

**戻り値:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

DataSourceType プロパティが DataSourceType.DoubleLiterals の場合、リテラル double を取得または設定します。読み取り/書き込み可能な double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

値を double に変換します。

**戻り値:**
double - Double 値
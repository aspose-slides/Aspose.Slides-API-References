---
title: ToDateTimeOffset()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定された String を DateTimeOffset に相当するものに変換します。
type: docs
weight: 430
url: /ja/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) メソッド

指定された[String](../../../system/string/)を[DateTimeOffset](../../../system/datetimeoffset/)に変換します。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 変換対象の文字列。文字列は XML dateTime 型の W3C 推奨事項のサブセットに準拠している必要があります。詳細は XML [Schema](../../../system.xml.schema/) 仕様の [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) セクションをご参照ください。 |

### 戻り値

指定された文字列の[DateTimeOffset](../../../system/datetimeoffset/)に相当するもの。

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) メソッド

指定された[String](../../../system/string/)を[DateTimeOffset](../../../system/datetimeoffset/)に変換します。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 変換対象の文字列。 |
| format | const [String](../../../system/string/)\& | **s** が変換される形式。format パラメーターは XML dateTime 型の W3C 推奨事項の任意のサブセットを指定できます。詳細は XML [Schema](../../../system.xml.schema/) 仕様の [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) セクションをご参照ください。文字列 **s** はこの形式に対して検証されます。 |

### 戻り値

指定された文字列の[DateTimeOffset](../../../system/datetimeoffset/)に相当するもの。

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) メソッド

指定された[String](../../../system/string/)を[DateTimeOffset](../../../system/datetimeoffset/)に変換します。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 変換対象の文字列。 |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | **s** を変換できる形式の配列。**formats** の各形式は XML dateTime 型の W3C 推奨事項の任意のサブセットです。詳細は XML [Schema](../../../system.xml.schema/) 仕様の [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) セクションをご参照ください。文字列 **s** はこれらの形式のいずれかに対して検証されます。 |

### 戻り値

指定された文字列の[DateTimeOffset](../../../system/datetimeoffset/)に相当するもの。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [DateTimeOffset](../../../system/datetimeoffset/)
* クラス [String](../../../system/string/)
* クラス [XmlConvert](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
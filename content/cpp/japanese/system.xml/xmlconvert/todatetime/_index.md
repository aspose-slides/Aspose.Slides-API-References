---
title: ToDateTime()
second_title: Aspose.Slides for C++ API リファレンス
description: String を DateTime に相当する形式に変換します。
type: docs
weight: 417
url: /ja/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) メソッド

[String](../../../system/string/) を [DateTime](../../../system/datetime/) に変換します。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 変換対象の文字列。 |

### 戻り値

[DateTime](../../../system/datetime/) に相当する文字列。

## XmlConvert::ToDateTime(const String\&, const String\&) メソッド

[String](../../../system/string/) を [DateTime](../../../system/datetime/) に変換します。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 変換対象の文字列。 |
| format | const [String](../../../system/string/)\& | 変換された [DateTime](../../../system/datetime/) に適用するフォーマット構造。使用できるフォーマットは "yyyy-MM-ddTHH:mm:sszzzzzz" とそのサブセットです。文字列はこのフォーマットに対して検証されます。 |

### 戻り値

[DateTime](../../../system/datetime/) に相当する文字列。

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) メソッド

[String](../../../system/string/) を [DateTime](../../../system/datetime/) に変換します。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 変換対象の文字列。 |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 変換された [DateTime](../../../system/datetime/) に適用するフォーマット構造を含む配列。使用できるフォーマットは "yyyy-MM-ddTHH:mm:sszzzzzz" とそのサブセットです。 |

### 戻り値

[DateTime](../../../system/datetime/) に相当する文字列。

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) メソッド

指定された XmlDateTimeSerializationMode を使用して [String](../../../system/string/) を [DateTime](../../../system/datetime/) に変換します。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 変換対象の [String](../../../system/string/) 値。 |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | UTC 日付の場合、日時をローカル時間に変換するか、協定世界時（UTC）として保持するかを指定する列挙値のいずれか。 |

### 戻り値

[String](../../../system/string/) に相当する [DateTime](../../../system/datetime/)。

## 関連項目

* 列挙型 [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [DateTime](../../../system/datetime/)
* クラス [String](../../../system/string/)
* クラス [XmlConvert](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
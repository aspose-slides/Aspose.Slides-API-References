---
title: ToDateTime()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 String 轉換為等價的 DateTime。
type: docs
weight: 417
url: /zh-hant/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) 方法


將 [String](../../../system/string/) 轉換為等價的 [DateTime](../../../system/datetime/)。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要轉換的字串。 |

### 回傳值

等價於字串的 [DateTime](../../../system/datetime/)。

## XmlConvert::ToDateTime(const String\&, const String\&) 方法


將 [String](../../../system/string/) 轉換為等價的 [DateTime](../../../system/datetime/)。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要轉換的字串。 |
| format | const [String](../../../system/string/)\& | 套用於已轉換的 [DateTime](../../../system/datetime/) 的格式結構。有效的格式包括 "yyyy-MM-ddTHH:mm:sszzzzzz" 及其子集。字串會依此格式進行驗證。 |

### 回傳值

等價於字串的 [DateTime](../../../system/datetime/)。

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) 方法


將 [String](../../../system/string/) 轉換為等價的 [DateTime](../../../system/datetime/)。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要轉換的字串。 |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 包含套用於已轉換的 [DateTime](../../../system/datetime/) 的格式結構的陣列。有效的格式包括 "yyyy-MM-ddTHH:mm:sszzzzzz" 及其子集。 |

### 回傳值

等價於字串的 [DateTime](../../../system/datetime/)。

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) 方法


使用指定的 XmlDateTimeSerializationMode，將 [String](../../../system/string/) 轉換為等價的 [DateTime](../../../system/datetime/)。

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要轉換的 [String](../../../system/string/) 值。 |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | 列舉值之一，用於指定日期是否應該轉換為本地時間，或在為 UTC 日期時保留為協調世界時 (UTC)。 |

### 回傳值

等價於 [String](../../../system/string/) 的 [DateTime](../../../system/datetime/)。

## 另請參閱

* Enum [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DateTime](../../../system/datetime/)
* Class [String](../../../system/string/)
* Class [XmlConvert](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
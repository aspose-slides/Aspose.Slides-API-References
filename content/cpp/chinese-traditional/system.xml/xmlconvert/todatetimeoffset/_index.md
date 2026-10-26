---
title: ToDateTimeOffset()
second_title: Aspose.Slides C++ API 參考文件
description: 將提供的 String 轉換為 DateTimeOffset 等效值。
type: docs
weight: 430
url: /zh-hant/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) 方法

將提供的 [String](../../../system/string/) 轉換為 [DateTimeOffset](../../../system/datetimeoffset/) 等效值。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要轉換的字串。字串必須符合 XML dateTime 型別的 W3C 推薦規範子集。欲取得更多資訊，請參閱 XML [Schema](../../../system.xml.schema/) 規範的 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 章節。 |

### 回傳值

提供之字串的 [DateTimeOffset](../../../system/datetimeoffset/) 等效值。

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) 方法


將提供的 [String](../../../system/string/) 轉換為 [DateTimeOffset](../../../system/datetimeoffset/) 等效值。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要轉換的字串。 |
| format | const [String](../../../system/string/)\& | 用於將 **s** 轉換的格式。format 參數可以是 XML dateTime 型別的 W3C 推薦規範子集。欲取得更多資訊，請參閱 XML [Schema](../../../system.xml.schema/) 規範的 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 章節。字串 **s** 會依此格式進行驗證。 |

### 回傳值

提供之字串的 [DateTimeOffset](../../../system/datetimeoffset/) 等效值。

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) 方法


將提供的 [String](../../../system/string/) 轉換為 [DateTimeOffset](../../../system/datetimeoffset/) 等效值。

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要轉換的字串。 |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | 可用來轉換 **s** 的格式陣列。**formats** 中的每個格式皆可為 XML dateTime 型別的 W3C 推薦規範子集。欲取得更多資訊，請參閱 XML [Schema](../../../system.xml.schema/) 規範的 [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) 章節。字串 **s** 會以其中一個格式進行驗證。 |

### 回傳值

提供之字串的 [DateTimeOffset](../../../system/datetimeoffset/) 等效值。

## 另見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [DateTimeOffset](../../../system/datetimeoffset/)
* 類別 [String](../../../system/string/)
* 類別 [XmlConvert](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
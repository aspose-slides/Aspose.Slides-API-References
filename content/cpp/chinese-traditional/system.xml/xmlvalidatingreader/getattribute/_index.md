---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 傳回具有指定名稱的屬性的值。
type: docs
weight: 443
url: /zh-hant/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) method

返回具有指定名稱的屬性的值。

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的限定名稱。 |

### 返回值

指定屬性的值。如果未找到屬性，將返回 **nullptr**。

## XmlValidatingReader::GetAttribute(String, String) method

返回具有指定本地名稱和命名空間統一資源標識符 (URI) 的屬性的值。

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 返回值

指定屬性的值。如果未找到屬性，將返回 **nullptr**。此方法不會移動讀取器。

## XmlValidatingReader::GetAttribute(int32_t) method

返回具有指定索引的屬性的值。

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | **int32_t** | 屬性的索引。索引從零開始。（第一個屬性的索引為 0。） |

### 返回值

指定屬性的值。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
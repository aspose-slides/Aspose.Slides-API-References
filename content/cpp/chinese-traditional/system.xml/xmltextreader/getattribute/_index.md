---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回具有指定名稱的屬性的值。
type: docs
weight: 495
url: /zh-hant/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) 方法

傳回具有指定名稱的屬性的值。

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的完全限定名稱。 |

### 傳回值

指定屬性的值。如果找不到該屬性，將傳回 **nullptr**。

## XmlTextReader::GetAttribute(String, String) 方法

傳回具有指定本機名稱和命名空間 URI 的屬性的值。

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本機名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 傳回值

指定屬性的值。如果找不到該屬性，將傳回 **nullptr**。此方法不會移動讀取器。

## XmlTextReader::GetAttribute(int32_t) 方法

傳回具有指定索引的屬性的值。

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | **int32_t** | 屬性的索引。索引是零基的。（第一個屬性的索引為 0。） |

### 傳回值

指定屬性的值。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
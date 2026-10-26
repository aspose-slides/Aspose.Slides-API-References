---
title: GetAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 傳回具有指定名稱的屬性的值。
type: docs
weight: 287
url: /zh-hant/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) 方法

傳回具有指定名稱的屬性的值。

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的合格名稱。 |

### 返回值

指定屬性的值。如果未找到該屬性，則返回 **nullptr**。

## XmlNodeReader::GetAttribute(String, String) 方法

傳回具有指定本地名稱和名稱空間 URI 的屬性的值。

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的名稱空間 URI。 |

### 返回值

指定屬性的值。如果未找到該屬性，則返回 **nullptr**。

## XmlNodeReader::GetAttribute(int32_t) 方法

傳回具有指定索引的屬性的值。

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| attributeIndex | **int32_t** | 屬性的索引。索引為零基。（第一個屬性的索引為 0。） |

### 返回值

指定屬性的值。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
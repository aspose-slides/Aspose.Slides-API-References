---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 將定位到具有指定名稱的屬性。
type: docs
weight: 508
url: /zh-hant/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) 方法

將定位到具有指定名稱的屬性。

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的限定名稱。 |

### 返回值

**true** 若找到屬性；否則 **false**。如果返回 **false**，閱讀器的位置不會改變。

## XmlTextReader::MoveToAttribute(String, String) 方法

將定位到具有指定本地名稱和命名空間 URI 的屬性。

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 返回值

**true** 若找到屬性；否則 **false**。如果返回 **false**，閱讀器的位置不會改變。

## XmlTextReader::MoveToAttribute(int32_t) 方法

將定位到具有指定索引的屬性。

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | **int32_t** | 屬性的索引。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
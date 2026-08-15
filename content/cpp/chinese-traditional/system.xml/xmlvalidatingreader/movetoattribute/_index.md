---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 參考文件
description: 將讀取器移動到具有指定名稱的屬性。
type: docs
weight: 456
url: /zh-hant/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) 方法

將讀取器移動到具有指定名稱的屬性。

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的限定名稱。 |

### 返回值

**true** 若找到屬性，否則為 **false**。若為 **false**，讀取器的位置不會改變。

## XmlValidatingReader::MoveToAttribute(String, String) 方法

將讀取器移動到具有指定本地名稱和命名空間統一資源標誌符 (URI) 的屬性。

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 返回值

**true** 若找到屬性，否則為 **false**。若為 **false**，讀取器的位置不會改變。

## XmlValidatingReader::MoveToAttribute(int32_t) 方法

將讀取器移動到具有指定索引的屬性。

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| i | **int32_t** | 屬性的索引。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
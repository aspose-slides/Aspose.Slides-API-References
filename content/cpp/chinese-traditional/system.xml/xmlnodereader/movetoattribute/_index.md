---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 將移至具有指定名稱的屬性。
type: docs
weight: 300
url: /zh-hant/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) 方法

將移至具有指定名稱的屬性。

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的限定名稱。 |

### 返回值

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlNodeReader::MoveToAttribute(String, String) 方法

將移至具有指定本機名稱和命名空間 URI 的屬性。

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 屬性的本機名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |

### 返回值

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlNodeReader::MoveToAttribute(int32_t) 方法

將移至具有指定索引的屬性。

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| attributeIndex | **int32_t** | 屬性的索引。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
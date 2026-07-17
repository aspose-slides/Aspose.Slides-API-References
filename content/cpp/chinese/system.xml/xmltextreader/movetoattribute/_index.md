---
title: MoveToAttribute()
second_title: Aspose.Slides C++ API 参考
description: 将移动到具有指定名称的属性。
type: docs
weight: 508
url: /zh/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) 方法

将移动到具有指定名称的属性。

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的限定名称。 |

### 返回值

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlTextReader::MoveToAttribute(String, String) 方法

将移动到具有指定本地名称和命名空间 URI 的属性。

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlTextReader::MoveToAttribute(int32_t) 方法

将移动到具有指定索引的属性。

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | 属性的索引。 |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API 参考
description: 将移动到具有指定名称的属性。
type: docs
weight: 300
url: /zh/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) 方法

将移动到具有指定名称的属性。

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的限定名称。 |

### 返回值

**true** 如果找到属性；否则为 **false**。如果为 **false**，读取器的位置不会改变。

## XmlNodeReader::MoveToAttribute(String, String) 方法

将移动到具有指定本地名称和命名空间 URI 的属性。

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

**true** 如果找到属性；否则为 **false**。如果为 **false**，读取器的位置不会改变。

## XmlNodeReader::MoveToAttribute(int32_t) 方法

将移动到具有指定索引的属性。

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeIndex | **int32_t** | 属性的索引。 |

## 另见

* Class [String](../../../system/string/)
* Class [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
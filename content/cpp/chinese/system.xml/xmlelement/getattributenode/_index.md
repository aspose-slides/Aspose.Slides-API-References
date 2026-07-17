---
title: GetAttributeNode()
second_title: Aspose.Slides 的 C++ API 参考
description: 返回具有指定名称的 XmlAttribute。
type: docs
weight: 248
url: /zh/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) 方法

返回具有指定名称的 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要检索的属性的名称。这是一个限定名称。它会与匹配节点的 **get_Name** 值进行匹配。 |

### 返回值

返回指定的 [XmlAttribute](../../xmlattribute/)，如果未找到匹配的属性，则返回 **nullptr**。

## XmlElement::GetAttributeNode(String, String) 方法

返回具有指定本地名称和命名空间 URI 的 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

返回指定的 [XmlAttribute](../../xmlattribute/)，如果未找到匹配的属性，则返回 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlAttribute](../../xmlattribute/)
* 类 [String](../../../system/string/)
* 类 [XmlElement](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
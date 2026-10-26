---
title: RemoveAttributeNode()
second_title: Aspose.Slides for C++ API 参考
description: 删除指定的 XmlAttribute。
type: docs
weight: 274
url: /zh/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) 方法

删除指定的 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | 要删除的 [XmlAttribute](../../xmlattribute/) 节点。如果已删除的属性有默认值，则会立即替换。 |

### 返回值

已删除的 [XmlAttribute](../../xmlattribute/)，如果 **oldAttr** 不是 [XmlElement](../) 的属性节点，则返回 **nullptr**。

## XmlElement::RemoveAttributeNode(String, String) 方法

删除由本地名称和命名空间 URI 指定的 [XmlAttribute](../../xmlattribute/)。（如果已删除的属性有默认值，则会立即替换）。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

已删除的 [XmlAttribute](../../xmlattribute/)，如果 [XmlElement](../) 没有匹配的属性节点，则返回 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlAttribute](../../xmlattribute/)
* 类 [XmlElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
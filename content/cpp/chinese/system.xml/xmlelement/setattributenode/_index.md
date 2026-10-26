---
title: SetAttributeNode()
second_title: Aspose.Slides C++ API 参考
description: 添加指定的 XmlAttribute。
type: docs
weight: 261
url: /zh/system.xml/xmlelement/setattributenode/
---
## XmlElement::SetAttributeNode(SharedPtr\<XmlAttribute\>) 方法


添加指定的 [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(SharedPtr<XmlAttribute> newAttr)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | 要添加到此元素属性集合的 [XmlAttribute](../../xmlattribute/) 节点。 |

### 返回值

如果属性替换了同名的现有属性，则返回旧的 [XmlAttribute](../../xmlattribute/)；否则，返回 **nullptr**。

## XmlElement::SetAttributeNode(String, String) 方法


添加指定的 [XmlAttribute](../../xmlattribute/).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::SetAttributeNode(String localName, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 属性的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 属性的命名空间 URI。 |

### 返回值

要添加的 [XmlAttribute](../../xmlattribute/)。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlAttribute](../../xmlattribute/)
* 类 [XmlElement](../)
* 类 [String](../../../system/string/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
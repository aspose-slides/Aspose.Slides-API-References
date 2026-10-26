---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的名称创建 XmlAttribute。
type: docs
weight: 274
url: /zh/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) 方法

使用指定的名称创建一个 [XmlAttribute](../../xmlattribute/)。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 属性的限定名称。如果名称包含冒号，[XmlNode::get_Prefix](../../xmlnode/get_prefix/) 值反映冒号前的部分，[XmlDocument::get_LocalName](../get_localname/) 值反映冒号后的部分。[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 保持为空，除非前缀是已识别的内置前缀，如 **xmlns**。在这种情况下，get_NamespaceURI 的值为 [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/)。 |

### 返回值

新的 [XmlAttribute](../../xmlattribute/)。

## XmlDocument::CreateAttribute(const String\&, const String\&) 方法

使用指定的限定名称和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 创建一个 [XmlAttribute](../../xmlattribute/)。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | 属性的限定名称。如果名称包含冒号，则 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 值反映冒号前的部分，[XmlDocument::get_LocalName](../get_localname/) 值反映冒号后的部分。 |
| namespaceURI | const [String](../../../system/string/)\& | 属性的 namespaceURI。如果限定名称包含 **xmlns** 前缀，则此参数必须为 [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/)。 |

### 返回值

新的 [XmlAttribute](../../xmlattribute/)。

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) 方法

使用指定的 [XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_LocalName](../get_localname/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 创建一个 [XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 属性的前缀（如果有）。[String::Empty](../../../system/string/empty/) 与 **nullptr** 等价。 |
| localName | const [String](../../../system/string/)\& | 属性的本地名称。 |
| namespaceURI | const [String](../../../system/string/)\& | 属性的 namespace URI（如果有）。[String::Empty](../../../system/string/empty/) 与 **nullptr** 等价。如果 **prefix** 为 **xmlns**，则此参数必须为 [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;)，否则会抛出异常。 |

### 返回值

新的 [XmlAttribute](../../xmlattribute/)。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlAttribute](../../xmlattribute/)
* 类 [String](../../../system/string/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
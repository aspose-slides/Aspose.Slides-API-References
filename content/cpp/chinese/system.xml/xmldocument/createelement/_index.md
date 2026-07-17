---
title: CreateElement()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的名称创建元素。
type: docs
weight: 339
url: /zh/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) 方法


创建一个元素，使用指定的名称。

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 元素的限定名称。如果名称包含冒号，则 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 值表示冒号前的部分，[XmlDocument::get_LocalName](../get_localname/) 值表示冒号后的部分。限定名称不能包含 **xmlns** 前缀。 |

### 返回值

新的[XmlElement](../../xmlelement/)。

## XmlDocument::CreateElement(const String\&, const String\&) 方法


创建一个[XmlElement](../../xmlelement/)，使用合格名称和[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)。

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | 元素的限定名称。如果名称包含冒号，则 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 值将表示冒号前的部分，[XmlDocument::get_LocalName](../get_localname/) 值将表示冒号后的部分。限定名称不能包含 **xmlns** 前缀。 |
| namespaceURI | const [String](../../../system/string/)\& | 元素的命名空间 URI。 |

### 返回值

新的[XmlElement](../../xmlelement/)。

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) 方法


创建一个元素，使用指定的[XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_LocalName](../get_localname/)和[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 新元素的前缀（如果有）。[String::Empty](../../../system/string/empty/) 与 **nullptr** 等价。 |
| localName | const [String](../../../system/string/)\& | 新元素的本地名称。 |
| namespaceURI | const [String](../../../system/string/)\& | 新元素的命名空间 URI（如果有）。[String::Empty](../../../system/string/empty/) 与 **nullptr** 等价。 |

### 返回值

新的[XmlElement](../../xmlelement/)。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlElement](../../xmlelement/)
* 类 [String](../../../system/string/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
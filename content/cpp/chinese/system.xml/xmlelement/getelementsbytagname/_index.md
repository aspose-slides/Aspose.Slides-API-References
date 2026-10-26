---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API 参考
description: "返回一个 XmlNodeList，其中包含所有匹配指定 XmlElement::get_Name 的后代元素列表。"
type: docs
weight: 287
url: /zh/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) 方法


返回一个 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配指定 [XmlElement::get_Name](../get_name/) 的后代元素列表。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要匹配的名称标签。这是一个限定名称。它与匹配节点的 **get_Name** 值进行比较。星号 (*) 是匹配所有标签的特殊值。 |

### 返回值

一个 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配节点的列表。如果没有匹配的节点，列表将为空。

## XmlElement::GetElementsByTagName(String, String) 方法


返回一个 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配指定 [XmlElement::get_LocalName](../get_localname/) 和 [XmlElement::get_NamespaceURI](../get_namespaceuri/) 值的后代元素列表。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要匹配的本地名称。星号 (*) 是匹配所有标签的特殊值。 |
| namespaceURI | [String](../../../system/string/) | 要匹配的命名空间 URI。 |

### 返回值

一个 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配节点的列表。如果没有匹配的节点，列表将为空。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNodeList](../../xmlnodelist/)
* 类 [String](../../../system/string/)
* 类 [XmlElement](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
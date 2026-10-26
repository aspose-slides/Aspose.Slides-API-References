---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个 XmlNodeList，包含所有匹配指定名称的后代元素列表。
type: docs
weight: 443
url: /zh/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) 方法

返回一个 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配指定名称的后代元素列表。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要匹配的限定名称。它会与匹配节点的 **get_Name** 值进行比较。特殊值 **\"*\"** 匹配所有标签。 |

### 返回值

返回一个 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配节点的列表。如果没有节点匹配 **name**，则返回的集合将为空。

## XmlDocument::GetElementsByTagName(String, String) 方法

返回一个 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配指定 [XmlDocument::get_LocalName](../get_localname/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 的后代元素列表。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要匹配的 LocalName。特殊值 **\"*\"** 匹配所有标签。 |
| namespaceURI | [String](../../../system/string/) | 要匹配的 NamespaceURI。 |

### 返回值

返回一个 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配节点的列表。如果没有节点匹配指定的 **localName** 和 **namespaceURI**，则返回的集合将为空。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNodeList](../../xmlnodelist/)
* 类 [String](../../../system/string/)
* 类 [XmlDocument](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
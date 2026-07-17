---
title: GetNamedItem()
second_title: Aspose.Slides for C++ API 参考
description: 检索指定名称的 XmlNode。
type: docs
weight: 14
url: /zh/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) 方法


检索指定名称的 [XmlNode](../../xmlnode/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要检索的节点的限定名称。它将与匹配节点的 [XmlNode::get_Name](../../xmlnode/get_name/) 值进行比较。 |

### 返回值

具有指定名称的 [XmlNode](../../xmlnode/)，如果未找到匹配的节点，则返回 **nullptr**。

## XmlNamedNodeMap::GetNamedItem(String, String) 方法


检索具有匹配的 [XmlNode::get_LocalName](../../xmlnode/get_localname/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 值的节点。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要检索的节点的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 要检索的节点的命名空间统一资源标识符（URI）。 |

### 返回值

具有匹配本地名称和命名空间 URI 的 [XmlNode](../../xmlnode/)，如果未找到匹配的节点，则返回 **nullptr**。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../../xmlnode/)
* 类 [String](../../../system/string/)
* 类 [XmlNamedNodeMap](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)
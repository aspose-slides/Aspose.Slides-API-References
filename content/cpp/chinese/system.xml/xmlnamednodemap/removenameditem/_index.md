---
title: RemoveNamedItem()
second_title: Aspose.Slides for C++ API 参考
description: 从 XmlNamedNodeMap 中删除节点。
type: docs
weight: 40
url: /zh/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) 方法

从 [XmlNamedNodeMap](../) 中删除节点。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要删除的节点的限定名称。名称将与匹配节点的 [XmlNode::get_Name](../../xmlnode/get_name/) 值进行匹配。 |

### 返回值

从此 [XmlNamedNodeMap](../) 中删除的 [XmlNode](../../xmlnode/)，如果未找到匹配的节点则返回 **nullptr**。

## XmlNamedNodeMap::RemoveNamedItem(String, String) 方法

删除具有匹配的 [XmlNode::get_LocalName](../../xmlnode/get_localname/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 值的节点。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要删除的节点的本地名称。 |
| namespaceURI | [String](../../../system/string/) | 要删除的节点的命名空间 URI。 |

### 返回值

已删除的 [XmlNode](../../xmlnode/)，如果未找到匹配的节点则返回 **nullptr**。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
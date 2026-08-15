---
title: RemoveNamedItem()
second_title: Aspose.Slides for C++ API 參考
description: 從 XmlNamedNodeMap 中移除節點。
type: docs
weight: 40
url: /zh-hant/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) 方法


從 [XmlNamedNodeMap](../) 中移除節點。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要移除之節點的限定名稱。名稱會與符合節點的 [XmlNode::get_Name](../../xmlnode/get_name/) 值進行比對。 |

### 返回值

從此 [XmlNamedNodeMap](../) 中移除的 [XmlNode](../../xmlnode/)，如果未找到匹配的節點，則返回 **nullptr**。

## XmlNamedNodeMap::RemoveNamedItem(String, String) 方法


移除具有匹配的 [XmlNode::get_LocalName](../../xmlnode/get_localname/) 與 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 值的節點。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要移除之節點的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 要移除之節點的命名空間 URI。 |

### 返回值

已移除的 [XmlNode](../../xmlnode/)，如果未找到匹配的節點，則返回 **nullptr**。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [String](../../../system/string/)
* 類別 [XmlNamedNodeMap](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
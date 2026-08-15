---
title: GetNamedItem()
second_title: Aspose.Slides for C++ API 參考
description: 根據名稱檢索指定的 XmlNode。
type: docs
weight: 14
url: /zh-hant/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) 方法

根據名稱檢索 [XmlNode](../../xmlnode/)。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要檢索的節點的限定名稱。它會與匹配節點的 [XmlNode::get_Name](../../xmlnode/get_name/) 值進行比對。 |

### 返回值

若找到匹配的節點，則返回具有指定名稱的 [XmlNode](../../xmlnode/)；如果未找到匹配的節點，則返回 **nullptr**。

## XmlNamedNodeMap::GetNamedItem(String, String) 方法

檢索具有匹配 [XmlNode::get_LocalName](../../xmlnode/get_localname/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 值的節點。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要檢索的節點的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 要檢索的節點的命名空間統一資源標識符 (URI)。 |

### 返回值

若找到匹配的節點，則返回具有匹配本地名稱和命名空間 URI 的 [XmlNode](../../xmlnode/)；如果未找到匹配的節點，則返回 **nullptr**。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
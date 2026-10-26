---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回一個 XmlNodeList，內含所有符合指定名稱的子孫元素清單。
type: docs
weight: 443
url: /zh-hant/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) 方法

傳回一個 [XmlNodeList](../../xmlnodelist/)，其中包含所有符合指定名稱的子孫元素清單。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要符合的限定名稱。它會與符合節點的 **get_Name** 值進行比對。特殊值 **\"*\"** 會匹配所有標籤。 |

### 傳回值

傳回一個 [XmlNodeList](../../xmlnodelist/)，其中包含所有符合的節點清單。如果沒有節點符合 **name**，則返回的集合將為空。

## XmlDocument::GetElementsByTagName(String, String) 方法

傳回一個 [XmlNodeList](../../xmlnodelist/)，其中包含所有符合指定 [XmlDocument::get_LocalName](../get_localname/) 和 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 的子孫元素清單。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要符合的 LocalName。特殊值 **\"*\"** 會匹配所有標籤。 |
| namespaceURI | [String](../../../system/string/) | 要符合的 NamespaceURI。 |

### 傳回值

傳回一個 [XmlNodeList](../../xmlnodelist/)，其中包含所有符合的節點清單。如果沒有節點符合指定的 **localName** 和 **namespaceURI**，則返回的集合將為空。

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNodeList](../../xmlnodelist/)
* 類別 [String](../../../system/string/)
* 類別 [XmlDocument](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
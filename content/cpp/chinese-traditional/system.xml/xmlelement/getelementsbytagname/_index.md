---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API 參考
description: "傳回一個 XmlNodeList，其中包含所有符合指定 XmlElement::get_Name 的後代元素列表。"
type: docs
weight: 287
url: /zh-hant/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) 方法

返回一個 [XmlNodeList](../../xmlnodelist/)，其中包含所有符合指定 [XmlElement::get_Name](../get_name/) 的後代元素列表。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要匹配的名稱標籤。這是一個限定名稱。它會與匹配節點的 **get_Name** 值進行比對。星號 (*) 為特殊值，可匹配所有標籤。 |

### 回傳值

一個 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配節點的列表。如果沒有匹配的節點，列表將為空。

## XmlElement::GetElementsByTagName(String, String) 方法

返回一個 [XmlNodeList](../../xmlnodelist/)，其中包含所有符合指定 [XmlElement::get_LocalName](../get_localname/) 和 [XmlElement::get_NamespaceURI](../get_namespaceuri/) 值的後代元素列表。

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 要匹配的本地名稱。星號 (*) 為特殊值，可匹配所有標籤。 |
| namespaceURI | [String](../../../system/string/) | 要匹配的命名空間 URI。 |

### 回傳值

一個 [XmlNodeList](../../xmlnodelist/)，其中包含所有匹配節點的列表。如果沒有匹配的節點，列表將為空。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNodeList](../../xmlnodelist/)
* 類別 [String](../../../system/string/)
* 類別 [XmlElement](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
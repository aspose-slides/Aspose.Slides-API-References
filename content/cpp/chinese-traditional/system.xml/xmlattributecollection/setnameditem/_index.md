---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API 參考
description: "使用 XmlNode::get_Name 結果新增一個 XmlNode。"
type: docs
weight: 14
url: /zh-hant/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) 方法

使用其 [XmlNode::get_Name](../../xmlnode/get_name/) 結果新增一個 [XmlNode](../../xmlnode/)。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 用於存放於此集合的屬性節點。之後可透過節點名稱存取此節點。若集合中已存在同名節點，將以新節點取代；否則，節點會被附加至集合末端。 |

### 返回值

如果 **node** 取代了具有相同名稱的現有節點，則回傳舊節點；否則，回傳新增的節點。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
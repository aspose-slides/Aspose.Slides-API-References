---
title: get_OldParent()
second_title: Aspose.Slides for C++ API 參考
description: "返回在操作開始前 XmlNode::get_ParentNode 的值。"
type: docs
weight: 27
url: /zh-hant/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() 方法


返回在操作開始前 [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) 的值。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```


### 返回值

在操作開始前 **ParentNode** 的值。 此方法如果節點沒有父節點，則返回 **nullptr**。 對於屬性節點，此方法返回 [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) 值。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlNodeChangedEventArgs](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
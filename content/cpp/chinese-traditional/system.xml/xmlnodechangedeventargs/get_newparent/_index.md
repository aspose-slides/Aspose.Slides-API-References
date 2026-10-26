---
title: get_NewParent()
second_title: Aspose.Slides for C++ API 參考
description: "在操作完成後，傳回 XmlNode::get_ParentNode 的值。"
type: docs
weight: 40
url: /zh-hant/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() 方法

在操作完成後，傳回 [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) 的值。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```

### 返回值

在操作完成後，**ParentNode** 的值。如果節點正在被移除，則此方法傳回 **nullptr**。對於屬性節點，此方法傳回 [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) 值。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [XmlNodeChangedEventArgs](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)
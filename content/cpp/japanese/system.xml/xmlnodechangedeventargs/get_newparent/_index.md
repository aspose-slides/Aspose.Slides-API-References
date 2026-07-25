---
title: get_NewParent()
second_title: Aspose.Slides for C++ API リファレンス
description: "操作が完了した後、XmlNode::get_ParentNode の値を返します。"
type: docs
weight: 40
url: /ja/system.xml/xmlnodechangedeventargs/get_newparent/
---
## XmlNodeChangedEventArgs::get_NewParent() メソッド


操作が完了した後の [XmlNode::get_ParentNode](../../xmlnode/get_parentnode/) の値を返します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_NewParent()
```


### 戻り値

操作が完了した後の **ParentNode** の値です。ノードが削除される場合、このメソッドは **nullptr** を返します。属性ノードの場合、このメソッドは [XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/) の値を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
---
title: get_OldParent()
second_title: Aspose.Slides for C++ APIリファレンス
description: "操作が開始される前の XmlNode::get_ParentNode の値を返します。"
type: docs
weight: 27
url: /ja/system.xml/xmlnodechangedeventargs/get_oldparent/
---
## XmlNodeChangedEventArgs::get_OldParent() メソッド

操作が開始される前の[XmlNode::get_ParentNode](../../xmlnode/get_parentnode/)の値を返します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlNodeChangedEventArgs::get_OldParent()
```

### 戻り値

操作が開始される前の**ParentNode**の値です。ノードに親がない場合、このメソッドは**nullptr**を返します。属性ノードの場合、このメソッドは[XmlAttribute::get_OwnerElement](../../xmlattribute/get_ownerelement/)の値を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlNodeChangedEventArgs](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
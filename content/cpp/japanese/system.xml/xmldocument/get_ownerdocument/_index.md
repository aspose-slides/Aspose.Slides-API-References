---
title: get_OwnerDocument()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードが属する XmlDocument を返します。
type: docs
weight: 79
url: /ja/system.xml/xmldocument/get_ownerdocument/
---
## XmlDocument::get_OwnerDocument() メソッド


現在のノードが属している [XmlDocument](../) を返します。

```cpp
SharedPtr<XmlDocument> System::Xml::XmlDocument::get_OwnerDocument() override
```


### 返り値

[XmlDocument](../) ノードについて ([XmlDocument::get_NodeType](../get_nodetype/) が [XmlNodeType::Document](../../xmlnodetype/) に等しい場合)、このメソッドは常に **nullptr** を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlDocument](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
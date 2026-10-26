---
title: get_ParentNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの親を返します（親を持つことができるノードの場合）。
type: docs
weight: 53
url: /ja/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() メソッド

このノードの親を返します（親を持つことができるノードの場合）。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### 戻り値

現在のノードの親である [XmlNode](../)。

## 備考

ノードが作成されたばかりでまだツリーに追加されていない場合、またはツリーから削除された場合、親は **nullptr** です。その他のすべてのノードについては、返される値はノードの [XmlNode::get_NodeType](../get_nodetype/) に依存します。次の表は **get_NodeType** メソッドの可能な戻り値を示しています。

| NodeType | ParentNode の戻り値 |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | `nullptr` を返します; これらのノードには親がありません。 |
| CDATA | CDATA セクションを含む要素またはエンティティ参照を返します。 |
| Comment | コメントを含む要素、エンティティ参照、ドキュメント型、またはドキュメントを返します。 |
| DocumentType | ドキュメントノードを返します。 |
| Element | 要素の親ノードを返します。要素がツリーのルートノードである場合、親はドキュメントノードです。 |
| EntityReference | エンティティ参照を含む要素、属性、またはエンティティ参照を返します。 |
| ProcessingInstruction | 処理指示を含むドキュメント、要素、ドキュメント型、またはエンティティ参照を返します。 |
| [Text](../../../system.text/)| テキストノードを含む親要素、属性、またはエンティティ参照を返します。 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
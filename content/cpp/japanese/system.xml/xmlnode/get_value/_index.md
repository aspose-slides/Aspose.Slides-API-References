---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: ノードの値を返します。
type: docs
weight: 14
url: /ja/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() メソッド

ノードの値を返します。

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### 戻り値

返される値はノードの[XmlNode::get_NodeType](../get_nodetype/)に依存します:

| 型 | 値 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性の値。 |
| CDATASection | CDATA セクションの内容。 |
| Comment | コメントの内容。 |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. XmlElement::InnerText または [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) の値を使用して、要素ノードの値にアクセスできます。 |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | ターゲットを除いた全体の内容。 |
| [Text](../../../system.text/)| テキストノードの内容。 |
| SignificantWhitespace | 空白文字です。空白は 1 つ以上のスペース文字、復帰、改行、またはタブで構成される場合があります。 |
| Whitespace | 空白文字です。空白は 1 つ以上のスペース文字、復帰、改行、またはタブで構成される場合があります。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣言の内容（つまり、`<?xml` と `?>` の間のすべて）。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
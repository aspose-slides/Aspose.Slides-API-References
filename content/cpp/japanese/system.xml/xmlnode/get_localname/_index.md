---
title: get_LocalName()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、ノードのローカル名を返します。
type: docs
weight: 209
url: /ja/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() メソッド


派生クラスでオーバーライドされた場合、ノードのローカル名を返します。

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### 戻り値

プレフィックスが除去されたノードの名前です。たとえば、**LocalName** は要素 **<bk:book>** の場合、**book** です。

## 備考



返される名前はノードの [XmlNode::get_NodeType](../get_nodetype/) に依存します: 

| 型 | 名前 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性のローカル名です。 |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | 文書タイプ名です。 |
| Element | 要素のローカル名です。 |
| Entity | エンティティの名前です。 |
| EntityReference | 参照されたエンティティの名前です。 |
| Notation | 表記の名前です。 |
| ProcessingInstruction | 処理指示のターゲットです。 |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## 関連項目

* クラス [String](../../../system/string/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
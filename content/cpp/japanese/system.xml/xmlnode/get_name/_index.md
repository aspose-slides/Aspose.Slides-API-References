---
title: get_Name()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、ノードの修飾名を返します。
type: docs
weight: 1
url: /ja/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() メソッド

派生クラスでオーバーライドされた場合、ノードの修飾名を返します。

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### 戻り値

ノードの修飾名です。

## 備考

返される名前はノードの [XmlNode::get_NodeType](../get_nodetype/) に依存します：

| 型 | 名前 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性の修飾名です。 |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | ドキュメントタイプ名です。 |
| Element | 要素の修飾名です。 |
| Entity | エンティティの名前です。 |
| EntityReference | 参照されたエンティティの名前です。 |
| Notation | 表記名です。 |
| ProcessingInstruction | 処理命令の対象です。 |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
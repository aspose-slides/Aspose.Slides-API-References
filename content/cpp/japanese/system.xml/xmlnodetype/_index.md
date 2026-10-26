---
title: XmlNodeType
second_title: Aspose.Slides for C++ API リファレンス
description: ノードのタイプを指定します。
type: docs
weight: 833
url: /ja/system.xml/xmlnodetype/
---
## XmlNodeType 列挙型


Specifies the type of node.

```cpp
enum class XmlNodeType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | これは、**Read** メソッドが呼び出されていない場合に [XmlReader](../xmlreader/) によって返されます。 |
| Element | 1 | 要素（例えば、**<item>**）。 |
| Attribute | 2 | 属性（例えば、**id='123'**）。 |
| Text | 3 | ノードのテキスト内容です。[XmlNodeType::Text](./) ノードは子ノードを持つことはできません。[XmlNodeType::Attribute](./)、[XmlNodeType::DocumentFragment](./)、[XmlNodeType::Element](./)、および [XmlNodeType::EntityReference](./) ノードの子ノードとして出現することができます。 |
| CDATA | 4 | CDATA セクション（例えば、**my escaped text**）。 |
| EntityReference | 5 | エンティティへの参照（例えば、**&num;**）。 |
| Entity | 6 | エンティティ宣言（例えば、**<!ENTITY...>**）。 |
| ProcessingInstruction | 7 | 処理指示（例えば、**<?pi test?>**）。 |
| Comment | 8 | コメント（例えば、****）。 |
| Document | 9 | ドキュメントツリーのルートとして、XML ドキュメント全体へのアクセスを提供するドキュメントオブジェクトです。 |
| DocumentType | 10 | 次のタグで示される文書型宣言（例えば、**<!DOCTYPE...>**）。 |
| DocumentFragment | 11 | 文書フラグメントです。 |
| Notation | 12 | 文書型宣言内の表記（例えば、**<!NOTATION...>**）。 |
| Whitespace | 13 | マークアップ間の空白です。 |
| SignificantWhitespace | 14 | 混在コンテンツモデル内のマークアップ間の空白、または **xml:space="preserve"** スコープ内の空白です。 |
| EndElement | 15 | 終了要素タグ（例えば、****）。 |
| EndEntity | 16 | [XmlReader](../xmlreader/) が [XmlReader::ResolveEntity](../xmlreader/resolveentity/) の呼び出しの結果としてエンティティ置換の末尾に達したときに返されます。 |
| XmlDeclaration | 17 | XML 宣言（例えば、**<?xml version='1.0'?>**）。[XmlNodeType::XmlDeclaration](./) ノードは文書内で最初のノードでなければなりません。子ノードを持つことはできません。[XmlNodeType::Document](./) ノードの子ノードです。バージョンやエンコーディング情報を提供する属性を持つことができます。 |

## 参照

* 名前空間 [System::Xml](../)
* ライブラリ [Aspose.Slides](../../)
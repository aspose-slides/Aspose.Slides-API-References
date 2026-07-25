---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードのテキスト値を返します。
type: docs
weight: 79
url: /ja/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() メソッド

現在のノードのテキスト値を返します。

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### 戻り値

返される値は、ノードの [XmlNodeReader::get_NodeType](../get_nodetype/) に依存します。

## 備考

次の表は、返す値を持つノード タイプを一覧しています。その他のすべてのノード タイプは [String::Empty](../../../system/string/empty/) を返します。

| Node Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性の値。 |
| CDATA| CDATA セクションの内容。 |
| Comment| コメントの内容。 |
| DocumentType| 内部サブセット。 |
| ProcessingInstruction| ターゲットを除く全体の内容。 |
| SignificantWhitespace| 混在コンテンツモデルにおけるマークアップ間の空白。 |
| [Text](../../../system.text/)| テキストノードの内容。 |
| Whitespace| マークアップ間の空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣言の内容。 |

## 関連項目

* クラス [String](../../../system/string/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
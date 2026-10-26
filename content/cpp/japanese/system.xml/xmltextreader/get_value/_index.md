---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードのテキスト値を返します。
type: docs
weight: 79
url: /ja/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() メソッド


現在のノードのテキスト値を返します。

```cpp
String System::Xml::XmlTextReader::get_Value() override
```


### 戻り値

戻り値はノードの [XmlTextReader::get_NodeType](../get_nodetype/) 値に依存します。

## 備考



次の表は、戻り値を持つノードタイプを一覧しています。その他のすべてのノードタイプは [String::Empty](../../../system/string/empty/) を返します。 

| Node Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性の値。 |
| CDATA| CDATA セクションの内容。 |
| Comment| コメントの内容。 |
| DocumentType| 内部サブセット。 |
| ProcessingInstruction| 対象を除いた全体の内容。 |
| SignificantWhitespace| `xml:space='preserve'` スコープ内の空白。 |
| [Text](../../../system.text/)| テキストノードの内容。 |
| Whitespace| マークアップ間の空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣言の内容。 |


## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
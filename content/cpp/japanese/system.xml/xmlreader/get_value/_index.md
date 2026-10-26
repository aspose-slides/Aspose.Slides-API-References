---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、現在のノードのテキスト値を取得します。
type: docs
weight: 92
url: /ja/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() メソッド

派生クラスでオーバーライドされた場合、現在のノードのテキスト値を取得します。

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### 戻り値

返される値はノードの [XmlReader::get_NodeType](../get_nodetype/) 値に依存します。

## 備考

以下の表は、値を返すノードタイプを一覧しています。その他のノードタイプは [String::Empty](../../../system/string/empty/) を返します。

| ノードタイプ | 値 |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| 属性の値。 |
| `CDATA`| CDATA セクションの内容。 |
| `Comment`| コメントの内容。 |
| `DocumentType`| 内部サブセット。 |
| `ProcessingInstruction`| ターゲットを除く全体の内容。 |
| `SignificantWhitespace`| 混在コンテンツモデルでマークアップ間にある空白。 |
| `[Text](../../../system.text/)`| テキストノードの内容。 |
| `Whitespace`| マークアップ間の空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣言の内容。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
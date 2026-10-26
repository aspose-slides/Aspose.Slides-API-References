---
title: get_Value()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードのテキスト値を返します。
type: docs
weight: 79
url: /ja/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() メソッド

現在のノードのテキスト値を返します。

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### 戻り値

返される値はノードの XmlValidatingReader::NodeType に依存します。

## 備考

以下の表は、返す値を持つノードタイプを一覧表示します。その他のノードタイプは [String::Empty](../../../system/string/empty/) を返します。

| ノード タイプ | 値 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性の値です。 |
| CDATA| CDATA セクションの内容です。 |
| Comment| コメントの内容です。 |
| DocumentType| 内部サブセットです。 |
| ProcessingInstruction| 対象を除く全体の内容です。 |
| SignificantWhitespace| 混在コンテンツ モデルでマークアップ間の空白です。 |
| [Text](../../../system.text/)| テキスト ノードの内容です。 |
| Whitespace| マークアップ間の空白です。 |
| [XmlDeclaration](../../xmldeclaration/)| 宣言の内容です。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
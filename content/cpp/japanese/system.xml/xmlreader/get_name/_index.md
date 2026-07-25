---
title: get_Name()
second_title: Aspose.Slides の C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、現在のノードの完全修飾名を取得します。
type: docs
weight: 27
url: /ja/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() メソッド

派生クラスでオーバーライドされた場合、現在のノードの完全修飾名を取得します。

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### 戻り値

現在のノードの完全修飾名です。例えば、要素 **<bk:book>** の **Name** は **bk:book** です。

## 備考

返される名前はノードの [XmlReader::get_NodeType](../get_nodetype/) 値に依存します。以下のノードタイプは示された値を返します。その他のすべてのノードタイプは空文字列を返します。 

| ノードタイプ | 名前 |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| 属性の名前です。 |
| `DocumentType`| 文書型の名前です。 |
| `Element`| タグ名です。 |
| `EntityReference`| 参照されたエンティティの名前です。 |
| `ProcessingInstruction`| 処理命令のターゲットです。 |
| [XmlDeclaration](../../xmldeclaration/)| リテラル文字列 `xml` です。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
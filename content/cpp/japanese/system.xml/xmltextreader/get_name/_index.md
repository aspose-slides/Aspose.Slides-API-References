---
title: get_Name()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 現在のノードの修飾名を返します。
type: docs
weight: 14
url: /ja/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() メソッド

現在のノードの修飾名を返します。

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### 戻り値

現在のノードの修飾名。例えば、要素 **<bk:book>** の **Name** は **bk:book** です。

## 備考

返される名前はノードの [XmlTextReader::get_NodeType](../get_nodetype/) 値に依存します。以下のノードタイプは一覧の値を返します。その他のノードタイプは空文字列を返します。

| ノードタイプ | 名前 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性の名前。 |
| DocumentType| ドキュメントタイプの名前。 |
| Element| タグ名。 |
| EntityReference| 参照されたエンティティの名前。 |
| ProcessingInstruction| 処理命令のターゲット。 |
| [XmlDeclaration](../../xmldeclaration/)| リテラル文字列 `xml`。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
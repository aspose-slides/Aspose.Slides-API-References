---
title: get_Name()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードの修飾名を返します。
type: docs
weight: 14
url: /ja/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() メソッド

現在のノードの修飾名を返します。

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### 戻り値

現在のノードの修飾名。例えば、要素 **<bk:book>** の **Name** は **bk:book** です。

## 備考

返される名前はノードの [XmlNodeReader::get_NodeType](../get_nodetype/) の値に依存します。以下のノードタイプは一覧の値を返します。他のすべてのノードタイプは空文字列を返します。

| ノードタイプ | 名前 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性の名前。 |
| DocumentType| ドキュメントタイプ名。 |
| Element| タグ名。 |
| EntityReference| 参照されているエンティティの名前。 |
| ProcessingInstruction| 処理命令のターゲット。 |
| [XmlDeclaration](../../xmldeclaration/)| リテラル文字列 `xml`。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: get_Name()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードの修飾名を返します。
type: docs
weight: 14
url: /ja/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() メソッド

現在のノードの修飾名を返します。

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### 戻り値

現在のノードの修飾名です。たとえば、要素 **<bk:book>** の **Name** は **bk:book** です。

## 備考

返される名前はノードの XmlValidatingReader::NodeType に依存します。次のノードタイプは一覧の値を返します。その他のすべてのノードタイプは空文字列を返します。

| ノードタイプ | 名前 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性の名前。 |
| DocumentType| 文書型名。 |
| Element| タグ名。 |
| EntityReference| 参照されたエンティティの名前。 |
| ProcessingInstruction| 処理命令のターゲット。 |
| [XmlDeclaration](../../xmldeclaration/)| 文字列 `xml`。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
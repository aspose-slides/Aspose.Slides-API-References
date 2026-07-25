---
title: MoveToContent()
second_title: Aspose.Slides for C++ API リファレンス
description: "現在のノードがコンテンツ（空白でないテキスト、CDATA、Element、EndElement、EntityReference、または EndEntity）ノードかどうかを確認します。ノードがコンテンツノードでない場合、リーダーは次のコンテンツノードまたはファイルの終端までスキップします。次のタイプのノードをスキップします：ProcessingInstruction、DocumentType、Comment、Whitespace、または SignificantWhitespace。"
type: docs
weight: 833
url: /ja/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() メソッド

現在のノードがコンテンツ（空白でないテキスト、**CDATA**、**Element**、**EndElement**、**EntityReference**、または **EndEntity**）ノードであるかどうかを確認します。ノードがコンテンツノードでない場合、リーダーは次のコンテンツノードまたはファイルの終端までスキップします。次のタイプのノードをスキップします：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace**、または **SignificantWhitespace**。

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### 戻り値

メソッドで見つかった現在のノードの[XmlReader::get_NodeType](../get_nodetype/)値、またはリーダーが入力ストリームの終端に達した場合は[XmlNodeType::None](../../xmlnodetype/)です。

## 関連項目

* Enum [XmlNodeType](../../xmlnodetype/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
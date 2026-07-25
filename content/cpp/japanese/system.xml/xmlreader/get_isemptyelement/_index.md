---
title: get_IsEmptyElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、現在のノードが空要素であるかどうかを示す値を取得します（例：<MyElement/>）。
type: docs
weight: 131
url: /ja/system.xml/xmlreader/get_isemptyelement/
---
## XmlReader::get_IsEmptyElement() メソッド

派生クラスでオーバーライドされた場合、現在のノードが空要素であるかどうかを示す値を取得します（例: **<MyElement/>**）。

```cpp
virtual bool System::Xml::XmlReader::get_IsEmptyElement()=0
```

### 戻り値

**true** は、現在のノードが要素 ([XmlReader::get_NodeType](../get_nodetype/) が [XmlNodeType::Element](../../xmlnodetype/) と等しい) で **/>** で終わる場合; それ以外の場合は **false**。

## 参照

* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
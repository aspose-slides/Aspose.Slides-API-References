---
title: get_IsEmptyElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードが空要素であるかどうかを示す値を返します（例: <MyElement/>）。
type: docs
weight: 118
url: /ja/system.xml/xmlvalidatingreader/get_isemptyelement/
---
## XmlValidatingReader::get_IsEmptyElement() メソッド

Returns a value indicating whether the current node is an empty element (for example, **<MyElement/>**).

```cpp
bool System::Xml::XmlValidatingReader::get_IsEmptyElement() override
```

### 戻り値

**true** は、現在のノードが要素 ([XmlValidatingReader::get_NodeType](../get_nodetype/) の値が [XmlNodeType::Element](../../xmlnodetype/) と等しい) で、**/>** で終わる場合です。そうでない場合は **false**。

## 参照

* クラス [XmlValidatingReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
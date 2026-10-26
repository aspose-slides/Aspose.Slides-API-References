---
title: get_IsEmptyElement()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードが空要素であるかどうかを示す値を返します（例: <MyElement/>）。
type: docs
weight: 131
url: /ja/system.xml/xmlnodereader/get_isemptyelement/
---
## XmlNodeReader::get_IsEmptyElement() メソッド


現在のノードが空要素であるかどうかを示す値を返します（例: **<MyElement/>**）。

```cpp
bool System::Xml::XmlNodeReader::get_IsEmptyElement() override
```


### 戻り値

**true** は、現在のノードが要素で ([XmlNodeReader::get_NodeType](../get_nodetype/) が [XmlNodeType::Element](../../xmlnodetype/) と等しい) かつ **/>** で終わる場合です。そうでなければ、**false** です。

## 参照

* クラス [XmlNodeReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
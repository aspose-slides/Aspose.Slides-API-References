---
title: MoveToFirst()
second_title: Aspose.Slides for C++ API リファレンス
description: XPathNavigator を現在のノードの最初の兄弟ノードに移動します。
type: docs
weight: 612
url: /ja/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() メソッド


現在のノードの最初の兄弟ノードに [XPathNavigator](../) を移動します。

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### 戻り値

**true** は、[XPathNavigator](../) が現在のノードの最初の兄弟ノードへの移動に成功した場合; **false** は、最初の兄弟が存在しない場合、または [XPathNavigator](../) が属性ノード上に現在位置している場合。[XPathNavigator](../) がすでに最初の兄弟に位置している場合、[XPathNavigator](../) は **true** を返し、位置を移動しません。[XPathNavigator::MoveToFirst](./) が最初の兄弟が存在しないため **false** を返す場合、または [XPathNavigator](../) が属性上に現在位置している場合、[XPathNavigator](../) の位置は変更されません。

## 参照

* クラス [XPathNavigator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)
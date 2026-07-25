---
title: get_Current()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合、この XPathNodeIterator の現在のコンテキストノード上に位置する XPathNavigator オブジェクトを取得します。
type: docs
weight: 1
url: /ja/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() メソッド


派生クラスでオーバーライドされた場合、現在のコンテキストノード上に位置するこの [XPathNodeIterator](../) の [XPathNavigator](../../xpathnavigator/) オブジェクトを取得します。

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```


### 戻り値

選択されたノードセットが取得されたコンテキストノード上に位置する [XPathNavigator](../../xpathnavigator/) オブジェクトです。[XPathNodeIterator::MoveNext](../movenext/) メソッドを呼び出して、[XPathNodeIterator](../) を選択されたセットの最初のノードに移動する必要があります。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XPathNavigator](../../xpathnavigator/)
* クラス [XPathNodeIterator](../)
* 名前空間 [System::Xml::XPath](../../)
* ライブラリ [Aspose.Slides](../../../)
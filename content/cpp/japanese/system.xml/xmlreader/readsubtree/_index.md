---
title: ReadSubtree()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のノードとそのすべての子孫を読み取るために使用できる新しい XmlReader インスタンスを返します。
type: docs
weight: 963
url: /ja/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() メソッド


現在のノードとそのすべての子孫を読み取るために使用できる新しい [XmlReader](../) インスタンスを返します。

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```


### 戻り値

[ReadState::Initial](../../readstate/) に設定された新しい XML リーダー インスタンスです。[XmlReader::Read](../read/) メソッドを呼び出すと、新しいリーダーは [XmlReader::ReadSubtree](./) メソッドの呼び出し前に現在だったノードに位置付けられます。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
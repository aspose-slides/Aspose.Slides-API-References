---
title: get_OldValue()
second_title: Aspose.Slides for C++ API リファレンス
description: ノードの元の値を返します。
type: docs
weight: 53
url: /ja/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() メソッド


ノードの元の値を返します。

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Return Value

ノードの元の値です。このメソッドは、ノードが属性でもテキストノードでもない場合、またはノードが挿入されている場合は **nullptr** を返します。**XmlDocument::NodeChanging** イベントで呼び出された場合、**get_OldValue** は変更が成功した場合に置き換えられるノードの現在の値を返します。**XmlDocument::NodeChanged** イベントで呼び出された場合、**get_OldValue** は変更前のノードの値を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNodeChangedEventArgs](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
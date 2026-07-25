---
title: get_NewValue()
second_title: Aspose.Slides for C++ API リファレンス
description: ノードの新しい値を返します。
type: docs
weight: 66
url: /ja/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() メソッド

ノードの新しい値です。

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### 戻り値

ノードの新しい値です。 このメソッドは、ノードが属性でもテキストノードでもない場合、またはノードが削除されようとしている場合、**nullptr** を返します。 **XmlDocument::NodeChanging** イベント内で呼び出された場合、変更が成功したときに **get_NewValue** はノードの値を返します。 **XmlDocument::NodeChanged** イベント内で呼び出された場合、**get_NewValue** はノードの現在の値を返します。

## 参照

* クラス [String](../../../system/string/)
* クラス [XmlNodeChangedEventArgs](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
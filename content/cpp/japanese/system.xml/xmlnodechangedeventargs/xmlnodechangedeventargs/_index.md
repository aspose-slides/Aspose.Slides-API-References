---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides for C++ API リファレンス
description: XmlNodeChangedEventArgs クラスの新しいインスタンスを初期化します。
type: docs
weight: 79
url: /ja/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor


[XmlNodeChangedEventArgs](../) クラスの新しいインスタンスを初期化します。

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | イベントを生成した[XmlNode](../../xmlnode/)。 |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | イベントを生成した[XmlNode](../../xmlnode/)の古い親[XmlNode](../../xmlnode/)。 |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | イベントを生成した[XmlNode](../../xmlnode/)の新しい親[XmlNode](../../xmlnode/)。 |
| oldValue | const [String](../../../system/string/)\& | イベントを生成した[XmlNode](../../xmlnode/)の古い値。 |
| newValue | const [String](../../../system/string/)\& | イベントを生成した[XmlNode](../../xmlnode/)の新しい値。 |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction。 |

## 参照

* 列挙型 [XmlNodeChangedAction](../../xmlnodechangedaction/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [String](../../../system/string/)
* クラス [XmlNodeChangedEventArgs](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
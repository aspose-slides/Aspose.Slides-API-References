---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。
type: docs
weight: 92
url: /ja/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) メソッド

このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** を指定すると、指定されたノードの下にあるサブツリーを再帰的にクローンします。**false** を指定すると、ノード自体だけをクローンします。[XmlEntityReference](../) ノードの場合、このメソッドは常に子を持たないエンティティ参照ノードを返します。置換テキストはノードが親に挿入されたときに設定されます。 |

### 戻り値

クローンされたノード。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlEntityReference](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
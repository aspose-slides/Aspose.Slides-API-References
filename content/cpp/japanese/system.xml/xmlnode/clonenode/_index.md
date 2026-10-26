---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: 派生クラスでオーバーライドされた場合に、ノードの複製を作成します。
type: docs
weight: 456
url: /ja/system.xml/xmlnode/clonenode/
---
## XmlNode::CloneNode(bool) メソッド

派生クラスでオーバーライドされた場合に、ノードの複製を作成します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::CloneNode(bool deep)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** を指定すると、指定されたノードの下のサブツリーを再帰的にクローンします。**false** を指定すると、ノード自体だけをクローンします。 |

### 戻り値

クローンされたノード。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
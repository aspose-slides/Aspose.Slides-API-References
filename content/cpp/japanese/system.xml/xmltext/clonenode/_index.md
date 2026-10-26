---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。
type: docs
weight: 79
url: /ja/system.xml/xmltext/clonenode/
---
## XmlText::CloneNode(bool) メソッド

このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlText::CloneNode(bool deep) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** を指定すると、指定されたノード以下のサブツリーを再帰的にクローンします。**false** を指定すると、ノード自身だけをクローンします。 |

### 戻り値

複製されたノード。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlText](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
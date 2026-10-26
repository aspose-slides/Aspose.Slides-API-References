---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。
type: docs
weight: 40
url: /ja/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) method


このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** を指定すると、指定されたノード以下のサブツリーを再帰的にクローンします。**false** を指定すると、ノード自体のみをクローンします。コメントノードは子を持たないため、パラメータ設定に関係なく、クローンされたノードには常にテキストコンテンツが含まれます。 |

### 戻り値

クローンされたノードです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlComment](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
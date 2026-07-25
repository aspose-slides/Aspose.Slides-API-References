---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。
type: docs
weight: 261
url: /ja/system.xml/xmldocument/clonenode/
---
## XmlDocument::CloneNode(bool) method

このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocument::CloneNode(bool deep) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** を指定すると、指定されたノード以下のサブツリーを再帰的にクローンします。**false** を指定すると、ノード自体だけをクローンします。 |

### 戻り値

クローンされた [XmlDocument](../) ノードです。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
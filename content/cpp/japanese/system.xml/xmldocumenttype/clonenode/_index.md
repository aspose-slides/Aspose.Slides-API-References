---
title: CloneNode()
second_title: Aspose.Slides for C++ API リファレンス
description: このノードの複製を作成します。
type: docs
weight: 118
url: /ja/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) method


このノードの複製を作成します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | **bool** | **true** を指定すると、指定されたノード以下のサブツリーを再帰的にクローンします。**false** を指定するとノード自体のみをクローンします。ドキュメント型ノードの場合、クローンされたノードは常にサブツリーを含みます。パラメータ設定に関係なく。 |

### 戻り値

クローンされたノードです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocumentType](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
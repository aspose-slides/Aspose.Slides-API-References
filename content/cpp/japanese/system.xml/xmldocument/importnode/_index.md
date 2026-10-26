---
title: ImportNode()
second_title: Aspose.Slides for C++ API リファレンス
description: 別のドキュメントからノードを現在のドキュメントにインポートします。
type: docs
weight: 469
url: /ja/system.xml/xmldocument/importnode/
---
## XmlDocument::ImportNode(SharedPtr\<XmlNode\>, bool) メソッド

別のドキュメントからノードを現在のドキュメントにインポートします。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ImportNode(SharedPtr<XmlNode> node, bool deep)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | インポートされるノードです。 |
| deep | **bool** | **true** を指定するとディープクローンを実行します。**false** を指定するとそれ以外です。 |

### 戻り値

インポートされた [XmlNode](../../xmlnode/)です。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlDocument](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
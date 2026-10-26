---
title: PrependChild()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたノードを、このノードの子ノードリストの先頭に追加します。
type: docs
weight: 261
url: /ja/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) メソッド


指定されたノードを、このノードの子ノードリストの先頭に追加します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 追加する[XmlNode](../../xmlnode/)。[XmlDocumentFragment](../../xmldocumentfragment/)の場合、ドキュメントフラグメントの全内容がこのノードの子リストに移動されます。 |

### 戻り値

追加された[XmlNode](../../xmlnode/)。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlAttribute](../)
* 名前空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)
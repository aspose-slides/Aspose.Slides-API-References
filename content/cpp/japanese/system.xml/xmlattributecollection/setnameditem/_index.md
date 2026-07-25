---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API リファレンス
description: "XmlNode::get_Name の結果を使用して XmlNode を追加します。"
type: docs
weight: 14
url: /ja/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) メソッド


[XmlNode](../../xmlnode/) をその [XmlNode::get_Name](../../xmlnode/get_name/) 結果を使用して追加します。

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | このコレクションに格納する属性ノード。ノードは後でノードの名前を使用してアクセスできるようになる。同じ名前のノードがすでにコレクションに存在する場合は新しいものに置き換えられ、存在しない場合はコレクションの最後に追加されます。 |

### 戻り値

**node** が同じ名前の既存ノードを置き換える場合は古いノードが返されます。置き換えが行われない場合は追加されたノードが返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlAttributeCollection](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
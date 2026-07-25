---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API リファレンス
description: "XmlNode::get_Name の値を使用して XmlNode を追加します。"
type: docs
weight: 27
url: /ja/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode>) メソッド


[XmlNode](../../xmlnode/) をその [XmlNode::get_Name](../../xmlnode/get_name/) 値を使用して追加します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)<[XmlNode](../../xmlnode/)> | [XmlNode](../../xmlnode/) を [XmlNamedNodeMap](../) に格納します。すでに同名のノードがマップに存在する場合、新しいものに置き換えられます。 |

### 戻り値

**node** が同じ名前の既存のノードを置き換える場合は、古いノードが返されます。それ以外の場合は、**nullptr** が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlNamedNodeMap](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
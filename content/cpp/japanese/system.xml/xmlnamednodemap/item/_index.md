---
title: Item()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたインデックスの XmlNamedNodeMap のノードを取得します。
type: docs
weight: 53
url: /ja/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) メソッド

指定されたインデックスのノードを [XmlNamedNodeMap](../) から取得します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 取得対象となるノードのインデックス位置です。[XmlNamedNodeMap](../) から取得します。インデックスはゼロベースで、最初のノードのインデックスは 0、最後のノードのインデックスは [XmlNamedNodeMap::get_Count](../get_count/) - 1 です。 |

### 戻り値

指定されたインデックスの [XmlNode](../../xmlnode/) を返します。**index** が 0 未満、または [XmlNamedNodeMap::get_Count](../get_count/) の値以上の場合、**nullptr** が返されます。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlNamedNodeMap](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
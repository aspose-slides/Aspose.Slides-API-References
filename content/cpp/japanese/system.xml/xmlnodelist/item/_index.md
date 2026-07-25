---
title: Item()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスのノードを取得します。
type: docs
weight: 14
url: /ja/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) メソッド

指定されたインデックスのノードを取得します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | ノードのリスト内のゼロベースインデックスです。 |

### 戻り値

コレクション内で指定されたインデックスを持つ [XmlNode](../../xmlnode/)。**index** がリスト内のノード数以上の場合、**nullptr** が返されます。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlNodeList](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
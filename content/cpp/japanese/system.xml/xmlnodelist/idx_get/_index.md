---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスのノードを返します。
type: docs
weight: 40
url: /ja/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get(int32_t) メソッド


指定されたインデックスのノードを返します。

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| i | **int32_t** | ノードのリストへのゼロベースインデックス。 |

### 戻り値

コレクション内で指定されたインデックスを持つ[XmlNode](../../xmlnode/)です。インデックスがリスト内のノード数以上の場合、**nullptr** を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [XmlNode](../../xmlnode/)
* クラス [XmlNodeList](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)
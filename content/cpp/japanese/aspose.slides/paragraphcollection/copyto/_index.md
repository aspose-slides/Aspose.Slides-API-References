---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: "ICollection の要素を System::Array にコピーし、特定の System::Array インデックスから開始します。"
type: docs
weight: 105
url: /ja/aspose.slides/paragraphcollection/copyto/
---
## ParagraphCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IParagraph\>\>, int32_t) メソッド

[ICollection](../../../system.collections.generic/icollection/) の要素を [System::Array](../../../system/array/) にコピーし、特定の [System::Array](../../../system/array/) インデックスから開始します。

```cpp
void Aspose::Slides::ParagraphCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IParagraph>> array, int32_t arrayIndex)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\>\> | 一次元の [System::Array](../../../system/array/) は、[ICollection](../../../system.collections.generic/icollection/) からコピーされた要素の宛先です。[System::Array](../../../system/array/) はゼロベースのインデックスである必要があります。 |
| arrayIndex | **int32_t** | *array* のコピー開始位置となるゼロベースのインデックスです。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraph](../../iparagraph/)
* クラス [ParagraphCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: "ICollection の要素を System::Array にコピーし、特定の System::Array インデックスから開始します。"
type: docs
weight: 66
url: /ja/aspose.slides.animation/behaviorcollection/copyto/
---
## BehaviorCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehavior\>\>, int32_t) メソッド

[ICollection](../../../system.collections.generic/icollection/) の要素を [System::Array](../../../system/array/) にコピーし、特定の [System::Array](../../../system/array/) インデックスから開始します。

```cpp
void Aspose::Slides::Animation::BehaviorCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehavior>> array, int32_t arrayIndex)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehavior](../../ibehavior/)\>\> | [ICollection](../../../system.collections.generic/icollection/) からコピーされた要素の宛先である一次元 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) はゼロベースインデックスである必要があります。 |
| arrayIndex | **int32_t** | *array* におけるコピー開始位置のゼロベースインデックス。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBehavior](../../ibehavior/)
* Class [BehaviorCollection](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
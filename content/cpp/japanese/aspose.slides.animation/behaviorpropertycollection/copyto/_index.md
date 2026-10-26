---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: "ICollection の要素を System::Array にコピーし、特定の System::Array インデックスから開始します。"
type: docs
weight: 66
url: /ja/aspose.slides.animation/behaviorpropertycollection/copyto/
---
## BehaviorPropertyCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IBehaviorProperty\>\>, int32_t) メソッド


[ICollection](../../../system.collections.generic/icollection/) の要素を [System::Array](../../../system/array/) にコピーし、特定の [System::Array](../../../system/array/) インデックスから開始します。

```cpp
void Aspose::Slides::Animation::BehaviorPropertyCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IBehaviorProperty>> array, int32_t arrayIndex) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IBehaviorProperty](../../ibehaviorproperty/)\>\> | [ICollection](../../../system.collections.generic/icollection/) からコピーされた要素の宛先となる一次元 [System::Array](../../../system/array/)。[System::Array](../../../system/array/) はゼロベースのインデックスを持つ必要があります。 |
| arrayIndex | **int32_t** | コピーが開始される *array* のゼロベースインデックス。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IBehaviorProperty](../../ibehaviorproperty/)
* クラス [BehaviorPropertyCollection](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: "ICollection の要素を System::Array にコピーし、特定の System::Array インデックスから開始します。"
type: docs
weight: 118
url: /ja/aspose.slides.charts/piesplitcustompointcollection/copyto/
---
## PieSplitCustomPointCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IChartDataPoint\>\>, int32_t) メソッド

[ICollection](../../../system.collections.generic/icollection/) の要素を [System::Array](../../../system/array/) にコピーし、特定の [System::Array](../../../system/array/) インデックスから開始します。

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IChartDataPoint>> array, int32_t arrayIndex) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\> | コピー元 [ICollection](../../../system.collections.generic/icollection/) からコピーされた要素の宛先となる一次元の [System::Array](../../../system/array/)。[System::Array](../../../system/array/) はゼロベースインデックスである必要があります。 |
| arrayIndex | **int32_t** | コピーが開始される *array* のゼロベースインデックス。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartDataPoint](../../ichartdatapoint/)
* Class [PieSplitCustomPointCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
---
title: Reorder()
second_title: Aspose.Slides for C++ API 參考
description: 將投影片從集合中移動到指定位置。
type: docs
weight: 105
url: /zh-hant/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) method

將投影片從集合中移動到指定位置。

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 目標索引。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 要移動。 |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) method

將投影片從集合中移動到指定位置。[Slides](../../) 會依其在列表中出現的順序，從 index 開始依序放置。

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 目標索引。 |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) 要移動。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
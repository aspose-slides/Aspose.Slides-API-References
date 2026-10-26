---
title: Reorder()
second_title: Aspose.Slides for C++ API 參考
description: 將投影片從集合中移動到指定位置。
type: docs
weight: 157
url: /zh-hant/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) 方法

將投影片從集合中移動到指定位置。

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 目標索引。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 待移動。 |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) 方法

將投影片從集合中移動到指定位置。[Slides](../../) 將從 index 開始依照它們在清單中的出現順序放置。

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 目標索引。 |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) 待移動。 |

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ISlide](../../islide/)
* 類別 [SlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
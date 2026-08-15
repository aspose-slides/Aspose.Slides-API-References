---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考
description: 將指定版面投影片的副本插入到集合的指定位置。
type: docs
weight: 14
url: /zh-hant/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) 方法

Inserts a copy of a specified layout slide to specified position of the collection.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 以進行複製。 |

### 回傳值

已插入的投影片。

## 備註

新的版面配置將會與此版面配置投影片集合的父母母版投影片連結。因此這相當於在 PowerPoint 中使用 "Use Destination Theme" 選項的複製/貼上。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [MasterLayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
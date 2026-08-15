---
title: InsertClone()
second_title: Aspose.Slides for C++ API 參考文件
description: 在集合的指定位置插入指定版面投影片的副本。
type: docs
weight: 14
url: /zh-hant/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) 方法

在集合的指定位置插入指定版面投影片的副本。

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | **int32_t** | 新投影片的索引。 |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 用於克隆。 |

### 回傳值

已插入的投影片。

## 備註

新的版面將與此版面投影片集合的母片投影片連結。因此這相當於在 PowerPoint 中使用「使用目標主題」選項的複製/貼上。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
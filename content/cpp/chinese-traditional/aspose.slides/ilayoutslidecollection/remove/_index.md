---
title: Remove()
second_title: Aspose.Slides for C++ API 參考
description: 從集合中移除版面配置。
type: docs
weight: 27
url: /zh-hant/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) 方法

從集合中移除版面配置。

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 要從集合中移除的版面投影片。 |
## 備註

1) 為避免拋出 PptxEditException，請先檢查版面的 HasDependingSlides 屬性。 2) 您也可以使用 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 方法來簡化程式碼。 
## 參見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [ILayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
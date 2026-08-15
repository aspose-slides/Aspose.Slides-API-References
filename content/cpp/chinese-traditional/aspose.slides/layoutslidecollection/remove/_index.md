---
title: Remove()
second_title: Aspose.Slides for C++ API 參考文件
description: 從集合中移除版面配置。
type: docs
weight: 66
url: /zh-hant/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) 方法


從集合中移除版面配置。

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | 要從集合中移除的版面投影片。 |
## 備註

1) 為避免拋出 PptxEditException，請先檢查版面的 HasDependingSlides 屬性。2) 也可以使用 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 方法來簡化程式碼。 
## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ILayoutSlide](../../ilayoutslide/)
* 類別 [LayoutSlideCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
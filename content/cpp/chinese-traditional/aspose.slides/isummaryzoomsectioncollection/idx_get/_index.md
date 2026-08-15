---
title: idx_get()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 取得指定索引處的元素。唯讀 ISummaryZoomSection.
type: docs
weight: 1
url: /zh-hant/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) 方法

取得指定索引處的元素。唯讀 [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## 備註

此範例示範透過索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomSection](../../isummaryzoomsection/)
* 類別 [ISummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
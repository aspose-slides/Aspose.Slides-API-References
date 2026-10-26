---
title: idx_get()
second_title: Aspose.Slides C++ API 參考文件
description: 取得指定索引處的元素。唯讀 ISummaryZoomSection.
type: docs
weight: 40
url: /zh-hant/aspose.slides/summaryzoomsectioncollection/idx_get/
---
## SummaryZoomSectionCollection::idx_get(int32_t) 方法

取得指定索引處的元素。唯讀 [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::idx_get(int32_t index) override
```

## 備註

此範例示範依索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomSection](../../isummaryzoomsection/)
* 類別 [SummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)
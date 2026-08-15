---
title: Clear()
second_title: Aspose.Slides for C++ API 參考
description: 從集合中移除所有 SummaryZoomSection 物件。
type: docs
weight: 105
url: /zh-hant/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() 方法

從集合中移除所有 [SummaryZoomSection](../../summaryzoomsection/) 物件。

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## 備註

本範例示範透過索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## 另請參閱

* 類別 [SummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)
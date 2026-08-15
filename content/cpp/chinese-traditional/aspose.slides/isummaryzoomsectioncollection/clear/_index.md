---
title: Clear()
second_title: Aspose.Slides for C++ API 參考文件
description: 從集合中移除所有 SummaryZoomSection 物件。
type: docs
weight: 66
url: /zh-hant/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() 方法

從集合中移除所有 [SummaryZoomSection](../../summaryzoomsection/) 物件。

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## 備註

此範例示範透過索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## 另見

* 類別 [ISummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
---
title: IndexOf()
second_title: Aspose.Slides C++ API 參考
description: 傳回指定 SummaryZoomSection 物件的索引。
type: docs
weight: 66
url: /zh-hant/aspose.slides/summaryzoomsectioncollection/indexof/
---
## SummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) 方法

傳回指定 [SummaryZoomSection](../../summaryzoomsection/) 物件的索引。

```cpp
int32_t Aspose::Slides::SummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) 物件用來尋找 [ISummaryZoomSection](../../isummaryzoomsection/)。 |

### 回傳值

[SummaryZoomSection](../../summaryzoomsection/) 物件的索引，若 [SummaryZoomSection](../../summaryzoomsection/) 物件不屬於此集合則回傳 -1。

## 備註

此範例示範如何透過索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomSection](../../isummaryzoomsection/)
* 類別 [SummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
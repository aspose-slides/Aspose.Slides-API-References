---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回指定 SummaryZoomSection 物件的索引。
type: docs
weight: 53
url: /zh-hant/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) 方法

傳回指定 [SummaryZoomSection](../../summaryzoomsection/) 物件的索引。

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) 物件，用於尋找 [ISummaryZoomSection](../../isummaryzoomsection/)。 |

### 回傳值

[SummaryZoomSection](../../summaryzoomsection/) 物件的索引，若 [SummaryZoomSection](../../summaryzoomsection/) 物件不屬於此集合則為 -1。

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

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
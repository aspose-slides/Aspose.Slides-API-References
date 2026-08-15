---
title: GetSummarySection()
second_title: Aspose.Slides for C++ API 參考
description: 傳回給定區段的 Summary Zoom Section 元素。
type: docs
weight: 92
url: /zh-hant/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) 方法

返回給定區段的 Summary Zoom [Section](../../section/) 元素。

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 用於尋找 [ISection](../../isection/) |

### 回傳值

[ISummaryZoomSection](../../isummaryzoomsection/) 或 null，如果集合未包含該區段的元素。

## 備註

此範例示範如何透過索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomSection](../../isummaryzoomsection/)
* 類別 [ISection](../../isection/)
* 類別 [SummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
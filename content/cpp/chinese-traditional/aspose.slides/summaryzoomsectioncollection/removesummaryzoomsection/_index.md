---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides for C++ API 參考
description: 從集合中移除 Summary Zoom Section 物件。
type: docs
weight: 79
url: /zh-hant/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) 方法

從集合中移除摘要縮放 [Section](../../section/) 物件。

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 其 Summary Zoom [Section](../../section/) 元素將被移除 [ISection](../../isection/)。 |
## 備註

此範例示範如何依索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISection](../../isection/)
* 類別 [SummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
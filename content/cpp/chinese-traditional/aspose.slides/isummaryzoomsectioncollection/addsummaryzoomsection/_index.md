---
title: AddSummaryZoomSection()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的 Summary Zoom Section 物件並將其加入集合
type: docs
weight: 14
url: /zh-hant/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) 方法

建立新的 Summary Zoom [Section](../../section/) 物件並將其加入集合

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 用於新的 Summary Zoom [Section](../../section/) 元素 [ISection](../../isection/) |

### 回傳值

已加入的 [ISummaryZoomFrame](../../isummaryzoomframe/) 元素

## 備註

如果集合中已經存在此區段的元素，則返回現有的元素。

此範例示範如何依索引取得 Summary Zoom [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomSection](../../isummaryzoomsection/)
* 類別 [ISection](../../isection/)
* 類別 [ISummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
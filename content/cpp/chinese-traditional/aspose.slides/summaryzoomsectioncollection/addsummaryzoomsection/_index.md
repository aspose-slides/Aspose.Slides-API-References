---
title: AddSummaryZoomSection()
second_title: Aspose.Slides C++ API 參考
description: 建立新的 Summary Zoom Section 物件並將其加入集合
type: docs
weight: 53
url: /zh-hant/aspose.slides/summaryzoomsectioncollection/addsummaryzoomsection/
---
## SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) 方法

建立新的 Summary Zoom [Section](../../section/) 物件並將其加入集合

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 用於新的 Summary Zoom [Section](../../section/) 元素 [ISection](../../isection/) |

### 傳回值

已加入 [ISummaryZoomFrame](../../isummaryzoomframe/) 元素

## 備註

如果集合中已存在此區段的元素，則回傳現有的元素。

此範例示範透過索引取得 Summary Zoom [Section](../../section/) 元素：

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomSection](../../isummaryzoomsection/)
* 類別 [ISection](../../isection/)
* 類別 [SummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)
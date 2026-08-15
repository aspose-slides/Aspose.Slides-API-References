---
title: GetSummarySection()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回給定節的摘要縮放區段元素。
type: docs
weight: 27
url: /zh-hant/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) 方法

傳回給定節的摘要縮放 [Section](../../section/) 元素。

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 以尋找 [ISection](../../isection/) |

### 回傳值

[ISummaryZoomSection](../../isummaryzoomsection/) 或 null，如果集合不包含該節的元素。

## 備註

此範例示範如何透過索引取得摘要縮放 [Section](../../section/) 元素：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISummaryZoomSection](../../isummaryzoomsection/)
* 類別 [ISection](../../isection/)
* 類別 [ISummaryZoomSectionCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)
---
title: GetSummarySection()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたセクションに対する Summary Zoom Section 要素を返します。
type: docs
weight: 27
url: /ja/aspose.slides/isummaryzoomsectioncollection/getsummarysection/
---
## ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) メソッド

指定されたセクションに対する Summary Zoom [Section](../../section/) 要素を返します。

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) to find [ISection](../../isection/) |

### 戻り値

[ISummaryZoomSection](../../isummaryzoomsection/) または、コレクションがそのセクションに要素を含まない場合は null。

## 備考



この例は、インデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています。
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomSection](../../isummaryzoomsection/)
* Class [ISection](../../isection/)
* Class [ISummaryZoomSectionCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
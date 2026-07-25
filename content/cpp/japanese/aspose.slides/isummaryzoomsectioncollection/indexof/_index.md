---
title: IndexOf()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された SummaryZoomSection オブジェクトのインデックスを返します。
type: docs
weight: 53
url: /ja/aspose.slides/isummaryzoomsectioncollection/indexof/
---
## ISummaryZoomSectionCollection::IndexOf(System::SharedPtr\<ISummaryZoomSection\>) メソッド

指定された [SummaryZoomSection](../../summaryzoomsection/) オブジェクトのインデックスを返します。

```cpp
virtual int32_t Aspose::Slides::ISummaryZoomSectionCollection::IndexOf(System::SharedPtr<ISummaryZoomSection> summaryZoomSection)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| summaryZoomSection | [System::SharedPtr](../../../system/sharedptr/)\<[ISummaryZoomSection](../../isummaryzoomsection/)\> | [SummaryZoomSection](../../summaryzoomsection/) オブジェクトを検索するための [ISummaryZoomSection](../../isummaryzoomsection/)。 |

### 戻り値

[SummaryZoomSection](../../summaryzoomsection/) オブジェクトのインデックス、またはこのコレクションに属さない [SummaryZoomSection](../../summaryzoomsection/) オブジェクトの場合は -1。

## 備考

この例は、インデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています。 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto selectedObject = collection->GetSummarySection(pres->get_Sections()->idx_get(2));
int32_t idx = collection->IndexOf(selectedObject);
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISummaryZoomSection](../../isummaryzoomsection/)
* クラス [ISummaryZoomSectionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
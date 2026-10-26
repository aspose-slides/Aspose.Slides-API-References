---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: Summary Zoom フレーム オブジェクトの ISummaryZoomSectionCollection を取得します。
type: docs
weight: 14
url: /ja/aspose.slides/isummaryzoomframe/get_summaryzoomcollection/
---
## ISummaryZoomFrame::get_SummaryZoomCollection() メソッド

Summary Zoom Frame オブジェクトの [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) を取得します。

```cpp
virtual System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::ISummaryZoomFrame::get_SummaryZoomCollection()=0
```

## 備考

この例は、インデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* クラス [ISummaryZoomFrame](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
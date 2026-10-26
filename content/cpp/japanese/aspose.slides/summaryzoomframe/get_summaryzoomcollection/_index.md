---
title: get_SummaryZoomCollection()
second_title: Aspose.Slides for C++ API リファレンス
description: Summary Zoom フレームオブジェクトの ISummaryZoomSectionCollection を取得します。
type: docs
weight: 14
url: /ja/aspose.slides/summaryzoomframe/get_summaryzoomcollection/
---
## SummaryZoomFrame::get_SummaryZoomCollection() メソッド


Summary Zoom Frame オブジェクトの [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/) を取得します。

```cpp
System::SharedPtr<ISummaryZoomSectionCollection> Aspose::Slides::SummaryZoomFrame::get_SummaryZoomCollection() override
```

## 備考


この例では、インデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示します: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::AsCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISummaryZoomSectionCollection](../../isummaryzoomsectioncollection/)
* クラス [SummaryZoomFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
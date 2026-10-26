---
title: idx_get()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスの要素を取得します。読み取り専用 ISummaryZoomSection。
type: docs
weight: 1
url: /ja/aspose.slides/isummaryzoomsectioncollection/idx_get/
---
## ISummaryZoomSectionCollection::idx_get(int32_t) メソッド


指定されたインデックスの要素を取得します。読み取り専用 [ISummaryZoomSection](../../isummaryzoomsection/).

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::idx_get(int32_t index)=0
```

## 備考


この例は、インデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています：
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto zoomSection = collection->idx_get(1);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISummaryZoomSection](../../isummaryzoomsection/)
* クラス [ISummaryZoomSectionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
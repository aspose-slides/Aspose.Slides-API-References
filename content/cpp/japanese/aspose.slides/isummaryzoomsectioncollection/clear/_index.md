---
title: Clear()
second_title: C++ 用 Aspose.Slides API リファレンス
description: コレクションからすべての SummaryZoomSection オブジェクトを削除します。
type: docs
weight: 66
url: /ja/aspose.slides/isummaryzoomsectioncollection/clear/
---
## ISummaryZoomSectionCollection::Clear() メソッド


コレクションからすべての [SummaryZoomSection](../../summaryzoomsection/) オブジェクトを削除します。

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::Clear()=0
```

## 備考


この例は、インデックスで Summary Zoom [Section](../../section/) 要素を取得することを示しています。 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## 参照

* クラス [ISummaryZoomSectionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
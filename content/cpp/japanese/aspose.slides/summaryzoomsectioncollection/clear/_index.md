---
title: Clear()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションからすべての SummaryZoomSection オブジェクトを削除します。
type: docs
weight: 105
url: /ja/aspose.slides/summaryzoomsectioncollection/clear/
---
## SummaryZoomSectionCollection::Clear() メソッド

コレクションからすべての [SummaryZoomSection](../../summaryzoomsection/) オブジェクトを削除します。

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::Clear() override
```

## 備考

この例は、インデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています。
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->Clear();
```

## 参照

* クラス [SummaryZoomSectionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides C++ 用 API リファレンス
description: コレクションから Summary Zoom Section オブジェクトを削除します。
type: docs
weight: 79
url: /ja/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) メソッド

コレクションから Summary Zoom [Section](../../section/) オブジェクトを削除します。

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) は、Summary Zoom [Section](../../section/) 要素を削除する対象です [ISection](../../isection/)。 |

## 備考

この例は、インデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISection](../../isection/)
* クラス [SummaryZoomSectionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクションから Summary Zoom Section オブジェクトを削除します。
type: docs
weight: 40
url: /ja/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) メソッド

コレクションから Summary Zoom [Section](../../section/) オブジェクトを削除します。

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) は、Summary Zoom [Section](../../section/) 要素を削除する対象です [ISection](../../isection/)。 |

## 備考

この例は、インデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています：
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
* クラス [ISummaryZoomSectionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
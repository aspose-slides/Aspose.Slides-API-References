---
title: AddSummaryZoomSection()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しい Summary Zoom セクション オブジェクトを作成し、コレクションに追加します
type: docs
weight: 14
url: /ja/aspose.slides/isummaryzoomsectioncollection/addsummaryzoomsection/
---
## ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr\<ISection\>) メソッド

新しい Summary Zoom [Section](../../section/) オブジェクトを作成し、コレクションに追加します

```cpp
virtual System::SharedPtr<ISummaryZoomSection> Aspose::Slides::ISummaryZoomSectionCollection::AddSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) 新しい Summary Zoom [Section](../../section/) 要素 [ISection](../../isection/) 用 |

### 戻り値

追加された [ISummaryZoomFrame](../../isummaryzoomframe/) 要素

## 備考

このセクションの要素がすでにコレクションに存在する場合、既存の要素が返されます。

この例はインデックスで Summary Zoom [Section](../../section/) 要素を取得する方法を示しています:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
auto newZoomSection = collection->AddSummaryZoomSection(pres->get_Sections()->idx_get(3));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISummaryZoomSection](../../isummaryzoomsection/)
* クラス [ISection](../../isection/)
* クラス [ISummaryZoomSectionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
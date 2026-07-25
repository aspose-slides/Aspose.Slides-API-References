---
title: GetSummarySection()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定されたセクションに対する Summary Zoom Section 要素を返します。
type: docs
weight: 92
url: /ja/aspose.slides/summaryzoomsectioncollection/getsummarysection/
---
## SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr\<ISection\>) メソッド

指定されたセクションに対して Summary Zoom [Section](../../section/) 要素を返します。

```cpp
System::SharedPtr<ISummaryZoomSection> Aspose::Slides::SummaryZoomSectionCollection::GetSummarySection(System::SharedPtr<ISection> section) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) を検索するための [ISection](../../isection/) |

### 戻り値

[ISummaryZoomSection](../../isummaryzoomsection/) または null、コレクションがそのセクションの要素を含まない場合。

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

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISummaryZoomSection](../../isummaryzoomsection/)
* クラス [ISection](../../isection/)
* クラス [SummaryZoomSectionCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
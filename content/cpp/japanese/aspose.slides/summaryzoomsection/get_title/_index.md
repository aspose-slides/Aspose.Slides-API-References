---
title: get_Title()
second_title: Aspose.Slides for C++ API リファレンス
description: Summary Zoom Section オブジェクトのテキストタイトルを返します。
type: docs
weight: 1
url: /ja/aspose.slides/summaryzoomsection/get_title/
---
## SummaryZoomSection::get_Title() メソッド


Summary Zoom [Section](../../section/) オブジェクトのテキストタイトルを返します。

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Title() override
```

## 備考


例: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## 参照

* クラス [String](../../../system/string/)
* クラス [SummaryZoomSection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
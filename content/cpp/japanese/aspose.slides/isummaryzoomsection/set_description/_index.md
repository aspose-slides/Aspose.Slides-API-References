---
title: set_Description()
second_title: Aspose.Slides for C++ API リファレンス
description: Summary Zoom Section オブジェクトのテキスト説明を返します。
type: docs
weight: 40
url: /ja/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) メソッド


Summary Zoom [Section](../../section/) オブジェクトのテキスト説明を返します。

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
```

## 備考


例:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## 参照

* クラス [String](../../../system/string/)
* クラス [ISummaryZoomSection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)
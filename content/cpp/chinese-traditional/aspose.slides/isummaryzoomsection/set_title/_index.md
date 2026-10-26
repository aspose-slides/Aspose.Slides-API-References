---
title: set_Title()
second_title: Aspose.Slides C++ API 參考
description: 傳回 Summary Zoom Section 物件的文字標題。
type: docs
weight: 14
url: /zh-hant/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) 方法

返回 Summary Zoom [Section](../../section/) 物件的文字標題。

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
```

## 備註

範例： 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## 參見

* 類別 [String](../../../system/string/)
* 類別 [ISummaryZoomSection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)
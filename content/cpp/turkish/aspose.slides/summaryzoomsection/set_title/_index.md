---
title: set_Title()
second_title: Aspose.Slides for C++ API Referansı
description: Summary Zoom Section nesnesinin metin başlığını döndürür.
type: docs
weight: 14
url: /tr/aspose.slides/summaryzoomsection/set_title/
---
## SummaryZoomSection::set_Title(System::String) yöntemi

Summary Zoom [Section](../../section/) nesnesinin metin başlığını döndürür.

```cpp
void Aspose::Slides::SummaryZoomSection::set_Title(System::String value) override
```

## Açıklamalar

Örnek:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Title(u"Title");
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [SummaryZoomSection](../)
* İsim alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)
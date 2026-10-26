---
title: set_Title()
second_title: Aspose.Slides için C++ API Referansı
description: Summary Zoom Section nesnesinin metin başlığını döndürür.
type: docs
weight: 14
url: /tr/aspose.slides/isummaryzoomsection/set_title/
---
## ISummaryZoomSection::set_Title(System::String) metot

Summary Zoom [Section](../../section/) nesnesinin metin başlığını döndürür.

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Title(System::String value)=0
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
* Sınıf [ISummaryZoomSection](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)
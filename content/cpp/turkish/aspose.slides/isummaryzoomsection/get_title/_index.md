---
title: get_Title()
second_title: Aspose.Slides için C++ API Referansı
description: Summary Zoom Section nesnesinin metin başlığını döndürür.
type: docs
weight: 1
url: /tr/aspose.slides/isummaryzoomsection/get_title/
---
## ISummaryZoomSection::get_Title() metod

Summary Zoom [Section](../../section/) nesnesinin metin başlığını döndürür.

```cpp
virtual System::String Aspose::Slides::ISummaryZoomSection::get_Title()=0
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

## Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ISummaryZoomSection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)
---
title: set_Description()
second_title: Aspose.Slides for C++ API Referansı
description: Summary Zoom Section nesnesinin metin açıklamasını döndürür.
type: docs
weight: 40
url: /tr/aspose.slides/isummaryzoomsection/set_description/
---
## ISummaryZoomSection::set_Description(System::String) metod


Summary Zoom [Section](../../section/) nesnesinin metin açıklamasını döndürür.

```cpp
virtual void Aspose::Slides::ISummaryZoomSection::set_Description(System::String value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto zoomSection = zoomFrame->get_SummaryZoomCollection()->idx_get(1);
zoomSection->set_Description(u"Description");
```

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ISummaryZoomSection](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
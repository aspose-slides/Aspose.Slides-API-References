---
title: get_Description()
second_title: Aspose.Slides için C++ API Referansı
description: Summary Zoom Section nesnesinin metin açıklamasını döndürür.
type: docs
weight: 27
url: /tr/aspose.slides/summaryzoomsection/get_description/
---
## SummaryZoomSection::get_Description() metot


Summary Zoom [Section](../../section/) nesnesinin metin açıklamasını döndürür.

```cpp
System::String Aspose::Slides::SummaryZoomSection::get_Description() override
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
* Sınıf [SummaryZoomSection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)
---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API Referansı
description: Section Zoom nesnesinin bağlandığı bölüm nesnesini alır. ISection'ı okuyun.
type: docs
weight: 1
url: /tr/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() metodu


[Section](../../section/) Zoom nesnesinin bağlandığı bölüm nesnesini alır. Okuyun [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Açıklamalar


Bu örnek, hedef bölümü değiştirmeyi gösterir ve bölüm yakınlaştırma nesnesi için yeni bir görüntü oluşturur: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISection](../../isection/)
* Sınıf [ISectionZoomFrame](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)
---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API Referansı
description: Section Zoom nesnesinin bağlandığı bölüm nesnesini ayarlar. ISection yazın.
type: docs
weight: 14
url: /tr/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) yöntemi

Zoom nesnesinin bağlandığı [Section](../../section/) bölüm nesnesini ayarlar. [ISection](../../isection/) yazın.

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
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
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)
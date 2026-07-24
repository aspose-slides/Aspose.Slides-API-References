---
title: set_TargetSection()
second_title: C++ için Aspose.Slides API Referansı
description: Section Zoom nesnesinin bağlandığı bölüm nesnesini ayarlar. ISection yazın.
type: docs
weight: 14
url: /tr/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) metot


[Section](../../section/) Zoom nesnesinin bağlandığı bölüm nesnesini ayarlar. Yazın [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Açıklamalar


Sonraki örnek, hedef bölümü değiştirmeyi gösterir ve bölüm yakınlaştırma nesnesi için yeni bir resim oluşturur: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISection](../../isection/)
* Sınıf [SectionZoomFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)
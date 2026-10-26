---
title: get_TargetSection()
second_title: Aspose.Slides için C++ API Referansı
description: Section Zoom nesnesinin bağlandığı bölüm nesnesini alır. ISection'ı okuyun.
type: docs
weight: 1
url: /tr/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() metod


Alır [Section](../../section/) Zoom nesnesinin bağlandığı bölüm nesnesini. Oku [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Açıklamalar


Sonraki örnek, hedef bölümü değiştirip bölüm yakınlaştırma nesnesi için yeni bir resim oluşturur: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISection](../../isection/)
* Sınıf [SectionZoomFrame](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
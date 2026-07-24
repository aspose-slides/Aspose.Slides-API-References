---
title: Shapes()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda Shape nesnelerinin tüm örneklerini toplar.
type: docs
weight: 1
url: /tr/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) metot

Sunumda [Presentation](../../../aspose.slides/presentation/) içinde tüm [Shape](../../../aspose.slides/shape/) örneklerini toplar.

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) şekilleri toplamak için |

### Return Value

Dönüş Değeri

Sunumda bulunan tüm şekillerin koleksiyonu

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // eğer şekil AutoShape ise, siyah katı bir kenarlık ekle
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IEnumerable](../../../system.collections.generic/ienumerable/)
* Sınıf [Shape](../../../aspose.slides/shape/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [Collect](../)
* AdAlanı [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)
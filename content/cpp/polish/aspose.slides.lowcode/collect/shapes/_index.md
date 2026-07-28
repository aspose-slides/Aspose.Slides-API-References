---
title: Shapes()
second_title: Aspose.Slides dla C++ – referencja API
description: Zbiera wszystkie wystąpienia Shape w Presentation.
type: docs
weight: 1
url: /pl/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) metoda


Zbiera wszystkie wystąpienia [Shape](../../../aspose.slides/shape/) w [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) do zbierania kształtów |

### Wartość zwracana

Zbiór wszystkich kształtów, które znajdują się w prezentacji
## Uwagi




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // jeśli kształt jest AutoShape, dodaj czarną solidną obwódkę
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




## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasa [Shape](../../../aspose.slides/shape/)
* Klasa [Presentation](../../../aspose.slides/presentation/)
* Klasa [Collect](../)
* Przestrzeń nazw [Aspose::Slides::LowCode](../../)
* Biblioteka [Aspose.Slides](../../../)
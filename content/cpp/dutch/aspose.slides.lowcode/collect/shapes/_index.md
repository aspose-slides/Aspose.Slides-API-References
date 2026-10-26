---
title: Shapes()
second_title: Aspose.Slides voor C++ API-referentie
description: Verzamelt alle instanties van Shape in de Presentatie.
type: docs
weight: 1
url: /nl/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) methode

Verzamelt alle instanties van [Shape](../../../aspose.slides/shape/) in de [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) om vormen te verzamelen |

### Retourwaarde

Collectie van alle vormen die in de presentatie aanwezig zijn
## Opmerkingen

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // als de vorm AutoShape is, voeg een zwarte solide rand toe
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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Klasse [Shape](../../../aspose.slides/shape/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [Collect](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)
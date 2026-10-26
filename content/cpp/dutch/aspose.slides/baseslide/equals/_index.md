---
title: Equals()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur van de dia en statische inhoud. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijv. SlideId, en dynamische inhoud, bijv. de huidige datumwaarde in Datumplaceholder.
type: docs
weight: 170
url: /nl/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) methode

Bepaalt of de twee [IBaseSlide](../../ibaseslide/) instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur van de dia en statische inhoud. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijv. SlideId, en dynamische inhoud, bijv. de huidige datumwaarde in Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | De [IBaseSlide](../../ibaseslide/) om te vergelijken met de huidige [IBaseSlide](../../ibaseslide/). |

### Retourwaarde

**true** als de opgegeven [IBaseSlide](../../ibaseslide/) gelijk is aan de huidige [IBaseSlide](../../ibaseslide/); anders, **false**.
## Opmerkingen

Het volgende voorbeeld toont hoe twee dia's te vergelijken. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBaseSlide](../../ibaseslide/)
* Klasse [BaseSlide](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
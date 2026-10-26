---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt effectieve portion-opmaakgegevens op met de toegepaste overerving.
type: docs
weight: 131
url: /nl/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() methode

Haalt effectieve portion opmaakgegevens op met de toegepaste overerving.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```

### Retourwaarde

Een [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Opmerkingen

Dit voorbeeld toont het ophalen van enkele effectieve portion opmaak-eigenschappen.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Klasse [PortionFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
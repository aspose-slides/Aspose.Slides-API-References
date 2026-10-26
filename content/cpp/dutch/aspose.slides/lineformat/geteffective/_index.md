---
title: GetEffective()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt effectieve lijnopmaakgegevens op met de overerving toegepast.
type: docs
weight: 417
url: /nl/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() methode

Haalt effectieve lijnopmaakgegevens op met de overerving toegepast.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```

### Retourwaarde

Een [ILineFormatEffectiveData](../../ilineformateffectivedata/).

## Opmerkingen

Dit voorbeeld toont het verkrijgen van de effectieve lijnopmaak-eigenschappen van een vorm.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Klasse [LineFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)
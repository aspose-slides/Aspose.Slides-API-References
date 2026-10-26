---
title: get_PortionFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een formatteringsobject dat expliciet ingestelde formatteringseigenschappen van het tekstgedeelte bevat zonder toegepaste overerving. Alleen-lezen IPortionFormat.
type: docs
weight: 1
url: /nl/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() methode

Retourneert een formatteringsobject dat expliciet ingestelde formatteringseigenschappen van het tekstgedeelte bevat zonder toegepaste overerving. Alleen-lezen [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Opmerkingen

Het formatteringsobject bevat de formatteringsparameters die alleen voor het huidige gedeelte zijn gedefinieerd; geërfde gegevens worden niet toegepast.

Om de effectieve waarden, inclusief geërfde waarden, te krijgen, gebruikt u de [PortionFormat::GetEffective](../../portionformat/geteffective/) methode.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPortionFormat](../../iportionformat/)
* Klasse [Portion](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
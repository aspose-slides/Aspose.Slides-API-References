---
title: get_PortionFormat()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar formateringsobjekt som innehåller uttryckligen angivna formateringsegenskaper för textdelen utan att ärvning tillämpas. Skrivskyddad IPortionFormat.
type: docs
weight: 1
url: /sv/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() metod

Returnerar formateringsobjekt som innehåller uttryckligen angivna formaterings-egenskaper för textdelen utan att ärvning tillämpas. Skrivskyddad [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Anmärkningar

Formateringsobjektet innehåller formateringsparametrarna som endast är definierade för den aktuella delen, ärvd data tillämpas inte.

För att få de effektiva värdena inklusive ärvda bör du använda [PortionFormat::GetEffective](../../portionformat/geteffective/)-metoden.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPortionFormat](../../iportionformat/)
* Klass [Portion](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
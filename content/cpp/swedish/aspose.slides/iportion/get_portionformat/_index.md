---
title: get_PortionFormat()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett formateringsobjekt som innehåller uttryckligen angivna formateringsegenskaper för textdelen utan någon ärvd tillämpning. Skrivskyddad IPortionFormat.
type: docs
weight: 1
url: /sv/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() metod

Returns formatting object which contains explicitly set formatting properties of the text portion with no inheritance applied. Skrivskyddad [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Anmärkningar

Formateringsobjektet innehåller de formateringsparametrar som definierats för den aktuella delen endast, ärvd data tillämpas inte.

För att få de effektiva värdena inklusive ärvda, använd [IPortionFormat::GetEffective](../../iportionformat/geteffective/) metod.
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IPortionFormat](../../iportionformat/)
* Klass [IPortion](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)
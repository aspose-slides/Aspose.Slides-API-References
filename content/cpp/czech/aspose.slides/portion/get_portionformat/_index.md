---
title: get_PortionFormat()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez uplatněné dědičnosti. Pouze pro čtení IPortionFormat.
type: docs
weight: 1
url: /cs/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() metoda

Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez aplikované dědičnosti. Pouze pro čtení [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Poznámky

Objekt formátování obsahuje parametry formátování definované pouze pro aktuální část, zděděná data nejsou použita.

Pro získání efektivních hodnot včetně zděděných použijte metodu [PortionFormat::GetEffective](../../portionformat/geteffective/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortionFormat](../../iportionformat/)
* Class [Portion](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
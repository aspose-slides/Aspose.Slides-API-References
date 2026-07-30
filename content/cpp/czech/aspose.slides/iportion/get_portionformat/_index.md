---
title: get_PortionFormat()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez aplikace dědičnosti. Pouze pro čtení IPortionFormat.
type: docs
weight: 1
url: /cs/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() metoda

Vrací objekt formátování, který obsahuje explicitně nastavené vlastnosti formátování textové části bez aplikace dědičnosti. Pouze pro čtení [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Poznámky

Objekt formátování obsahuje parametry formátování definované pouze pro aktuální část, zděděná data nejsou aplikována.

Chcete-li získat efektivní hodnoty včetně zděděných, použijte [IPortionFormat::GetEffective](../../iportionformat/geteffective/) metodu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPortionFormat](../../iportionformat/)
* Třída [IPortion](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
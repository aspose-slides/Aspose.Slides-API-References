---
title: get_PortionFormat()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca obiekt formatowania, który zawiera explicite ustawione właściwości formatowania fragmentu tekstu bez zastosowania dziedziczenia. Tylko do odczytu IPortionFormat.
type: docs
weight: 1
url: /pl/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() metoda

Zwraca obiekt formatowania, który zawiera explicite ustawione właściwości formatowania fragmentu tekstu bez zastosowania dziedziczenia. Tylko do odczytu [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Uwagi

Obiekt formatowania zawiera parametry formatowania zdefiniowane wyłącznie dla bieżącego fragmentu, dziedziczone dane nie są stosowane.

Aby uzyskać wartości efektywne, w tym dziedziczone, użyj metody [PortionFormat::GetEffective](../../portionformat/geteffective/).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPortionFormat](../../iportionformat/)
* Klasa [Portion](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
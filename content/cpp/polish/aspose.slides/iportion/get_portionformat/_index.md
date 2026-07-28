---
title: get_PortionFormat()
second_title: Aspose.Slides dla C++ - referencja API
description: Zwraca obiekt formatowania, który zawiera jawnie ustawione właściwości formatowania fragmentu tekstu bez zastosowanego dziedziczenia. Tylko do odczytu IPortionFormat.
type: docs
weight: 1
url: /pl/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() metoda

Zwraca obiekt formatowania, który zawiera jawnie ustawione właściwości formatowania fragmentu tekstu bez zastosowanego dziedziczenia. Tylko do odczytu [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Uwagi

Obiekt formatowania zawiera parametry formatowania zdefiniowane wyłącznie dla bieżącego fragmentu, odziedziczone dane nie są stosowane.

Aby uzyskać wartości skuteczne, w tym dziedziczone, użyj metody [IPortionFormat::GetEffective](../../iportionformat/geteffective/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IPortionFormat](../../iportionformat/)
* Klasa [IPortion](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)
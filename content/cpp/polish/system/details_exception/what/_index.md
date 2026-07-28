---
title: what()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Implementuje metodę what(), która jest wywoływana przez klasę ExceptionWrapper. Mimo że ta klasa nie dziedziczy po std::exception, klasy pochodne mogą używać chronionych/prywatnych członków, aby zaimplementować swoją logikę. Przeniesienie implementacji tej metody do ExceptionWrapper może zepsuć tę logikę."
type: docs
weight: 105
url: /pl/system/details_exception/what/
---
## Details_Exception::what() const metoda


Implementuje metodę [what()](./) która jest wywoływana przez klasę [ExceptionWrapper](../../exceptionwrapper/). Mimo że ta klasa nie jest dziedziczona po std::exception, klasy pochodne mogą używać chronionych/prywatnych pól, aby zaimplementować swoją logikę. Przeniesienie implementacji tej metody do [ExceptionWrapper](../../exceptionwrapper/) może zepsuć tę logikę.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```


### Wartość zwracana

Opis wyjątku.

## Zobacz także

* Klasa [Details_Exception](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)
---
title: MemoryMarshal
second_title: Aspose.Slides dla C++ – Referencja API
description: Zapewnia implementację marshalowania pamięci. Tylko w celu kompatybilności z przetłumaczonym kodem, ponieważ po stronie C++ nie jest obsługiwany żaden zarządzany kod. To jest typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 27
url: /pl/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal klasa

Zapewnia implementację marshalowania pamięci. Tylko w celu kompatybilności z przetłumaczonym kodem, ponieważ żaden zarządzany kod nie jest obsługiwany po stronie C++. To jest typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.

```cpp
class MemoryMarshal
```
## Metody

| Metoda | Opis |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Rzutuje [Span](../../system/span/) jednego typu prymitywnego T na [Span](../../system/span/) bajtów. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Rzutuje [Span](../../system/span/) jednego typu prymitywnego TFrom na inny typ prymitywny TTo. |
## Zobacz także

* Przestrzeń nazw [System::Runtime::InteropServices](../)
* Biblioteka [Aspose.Slides](../../)
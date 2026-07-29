---
title: MemoryMarshal
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller implementering av minnesmarshaling. Endast för kompatibilitet med översatt kod, eftersom ingen hanterad kod stöds på C++-sidan. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 27
url: /sv/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal klass

Tillhandahåller implementering av minnesmarshaling. Endast för kompatibilitet med översatt kod, eftersom ingen hanterad kod stöds på C++-sidan. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class MemoryMarshal
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Kastar en [Span](../../system/span/) av en primitiv typ T till [Span](../../system/span/) av byte. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Kastar en [Span](../../system/span/) av en primitiv typ TFrom till en annan primitiv typ TTo. |
## Se även

* Namnrymd [System::Runtime::InteropServices](../)
* Bibliotek [Aspose.Slides](../../)
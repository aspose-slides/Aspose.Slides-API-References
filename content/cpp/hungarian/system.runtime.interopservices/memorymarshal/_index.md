---
title: MemoryMarshal
second_title: Aspose.Slides for C++ API referencia
description: Memória marshalling megvalósítást biztosít. Csak a lefordított kód kompatibilitásához, mivel a C++ oldalon nem támogatott a kezelt kód. Ez egy statikus típus, amelynek nincs példányszolgáltatása. Soha ne hozzon létre példányokat ebből semmilyen módon.
type: docs
weight: 27
url: /hu/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal osztály


Memória marshalling megvalósítást biztosít. Csak a lefordított kód kompatibilitásához, mivel a C++ oldalon nem támogatott a kezelt kód. Ez egy statikus típus, amelynek nincs példányszolgáltatása. Soha ne hozzon létre példányokat ebből semmilyen módon.

```cpp
class MemoryMarshal
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Átalakít egy [Span](../../system/span/) egy primitív T típusú értéket [Span](../../system/span/) bájtokra. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Átalakít egy [Span](../../system/span/) egy primitív TFrom típusú értéket egy másik primitív TTo típusúra. |
## Lásd még

* Névtere [System::Runtime::InteropServices](../)
* Könyvtár [Aspose.Slides](../../)
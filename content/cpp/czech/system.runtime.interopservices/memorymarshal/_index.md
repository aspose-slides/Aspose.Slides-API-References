---
title: MemoryMarshal
second_title: Aspose.Slides pro C++ Referenční příručka API
description: Poskytuje implementaci memory marshalling. Pouze pro kompatibilitu s přeloženým kódem, protože na straně C++ není podporován žádný spravovaný kód. Jedná se o statický typ bez instančních služeb. Neměli byste jej nikdy vytvářet žádným způsobem.
type: docs
weight: 27
url: /cs/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal třída

Poskytuje implementaci memory marshalling. Pouze pro kompatibilitu s přeloženým kódem, protože na straně C++ není podporován žádný spravovaný kód. Jedná se o statický typ bez instančních služeb. Neměli byste jej nikdy vytvářet žádným způsobem.

```cpp
class MemoryMarshal
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Převádí [Span](../../system/span/) jednoho primitivního typu T na [Span](../../system/span/) bajtů. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Převádí [Span](../../system/span/) jednoho primitivního typu TFrom na jiný primitivní typ TTo. |

## Viz také

* Jmenný prostor [System::Runtime::InteropServices](../)
* Knihovna [Aspose.Slides](../../)
---
title: Span
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett sammanhängande område av godtyckligt minne som liknar C++20:s std::span."
type: docs
weight: 1262
url: /sv/system/span/
---
## Span-klass

Representerar ett sammanhängande område av godtyckligt minne som liknar C++20:s std::span.

```cpp
template<typename T>class Span : public System::Details::SpanCore<T, Span<T>, Span<T>>
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i span. Denna klass tillhandahåller ett typsäkert sätt att arbeta med sammanhängande sekvenser av objekt. Den kan användas för att omsluta arrayer, stackarrayer eller råpekare samtidigt som den upprätthåller gränskontroll. [Span](./) äger inte minnet den pekar på - det är bara en vy av befintligt minne. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [Clear](./clear/)() const | Rensar innehållet i span genom att sätta alla element till standardvärde. |
| void [Fill](./fill/)(const T\&) const | Fyller span med det angivna värdet. |
| static [ThisType](./) [to_Span](./to_span/)(const typename BaseType::ArrayPtrT\&) | Omvandlar en array till en [Span](./). |

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
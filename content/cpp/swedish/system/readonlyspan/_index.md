---
title: ReadOnlySpan
second_title: Aspose.Slides för C++ API-referens
description: Avsedd att användas inom Span-klass.
type: docs
weight: 1210
url: /sv/system/readonlyspan/
---
## ReadOnlySpan klass

Forward to use within [Span](../span/) klass.

```cpp
template<typename T>class ReadOnlySpan : public System::Details::SpanCore<const T, ReadOnlySpan<T>, Span<T>>
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannen. Denna klass tillhandahåller ett typ-säkert sätt att arbeta med sammanhängande sekvenser av objekt på ett read-only-sätt. Den kan användas för att omsluta arrayer, stack-arrayer eller råa pekare samtidigt som gränskontroll upprätthålls. [ReadOnlySpan](./) äger inte minnet den pekar på - den är bara en vy över befintligt minne. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [ReadOnlySpan](./readonlyspan/)(const [Span](../span/)\<T\>\&) | Skapar ett read-only-spann från ett reguljärt spann. |
| static [ThisType](./) [to_ReadOnlySpan](./to_readonlyspan/)(const typename BaseType::ArrayPtrT\&) | Konverterar en array till en [ReadOnlySpan](./). |

## Anmärkningar

Representerar ett read-only-sammanhängande område av godtyckligt minne.

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
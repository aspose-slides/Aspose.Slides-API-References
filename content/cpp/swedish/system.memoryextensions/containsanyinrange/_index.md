---
title: ContainsAnyInRange()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett skrivskyddat spann innehåller något element inom det angivna intervallet.
type: docs
weight: 92
url: /sv/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

Kontrollerar om ett skrivskyddat spann innehåller något element inom det angivna intervallet.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannet (måste vara jämförbara) |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Spannet att söka i |
| lowInclusive | const T\& | Den nedre gränsen (inkluderande) |
| highInclusive | const T\& | Den övre gränsen (inkluderande) |

### Returvärde

true om något element inom intervallet hittas, otherwise false

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

Kontrollerar om ett ändringsbart spann innehåller något element inom det angivna intervallet.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av element i spannet (måste vara jämförbara) |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Det ändringsbara spannet att söka i |
| lowInclusive | const T\& | Den nedre gränsen (inkluderande) |
| highInclusive | const T\& | Den övre gränsen (inkluderande) |

### Returvärde

true om något element inom intervallet hittas, otherwise false

## Se också

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)
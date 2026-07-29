---
title: LastIndexOfImpl()
second_title: Aspose.Slides för C++ API-referens
description: Hittar det sista indexet för ett värde i ett span.
type: docs
weight: 14
url: /sv/system.memoryextensions.details/lastindexofimpl/
---
## System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan\<T\>\&, int32_t, const T\&) funktion

Hittar det sista indexet för ett värde i ett span.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::LastIndexOfImpl(const ReadOnlySpan<T> &searchSpace, int32_t length, const T &value)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av element i span |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| searchSpace | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [Span](../../system/span/) att söka |
| length | **int32_t** | Längd att söka inom |
| value | const T\& | Värde att hitta |

### Returvärde

Det sista indexet för värdet, eller -1 om det inte hittas

## Se även

* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Namnrymd [System::MemoryExtensions::Details](../)
* Bibliotek [Aspose.Slides](../../)
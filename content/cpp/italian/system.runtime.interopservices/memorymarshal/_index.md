---
title: MemoryMarshal
second_title: Aspose.Slides per il Riferimento API di C++
description: Fornisce un'implementazione di marshalling della memoria. Solo per compatibilità con codice tradotto, poiché nessun codice gestito è supportato sul lato C++. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso con alcun mezzo.
type: docs
weight: 27
url: /it/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal classe


Fornisce un'implementazione di marshalling della memoria. Solo per compatibilità con codice tradotto, poiché non è supportato alcun codice gestito sul lato C++. Questo è un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso con alcun mezzo.

```cpp
class MemoryMarshal
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Converte un [Span](../../system/span/) di un tipo primitivo T in [Span](../../system/span/) di byte. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Converte un [Span](../../system/span/) di un tipo primitivo TFrom in un altro tipo primitivo TTo. |
## Vedi anche

* Spazio dei nomi [System::Runtime::InteropServices](../)
* Libreria [Aspose.Slides](../../)
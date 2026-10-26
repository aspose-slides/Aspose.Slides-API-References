---
title: ReadAsync()
second_title: Aspose.Slides för C++ API-referens
description: Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbrottsförfrågningar.
type: docs
weight: 40
url: /sv/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metod


Läser asynkront en följd av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbrottsförfrågningar.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytearrayen att skriva de lästa byten till. |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på. |
| count | **int32_t** | Antalet byte att läsa. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token för att övervaka avbrottsförfrågningar. |

### Returvärde

Ett task-objekt som representerar den asynkrona läsoperationen. Värdet för TResult-parametern innehåller det totala antalet byte som lästs in i buffer. Resultatvärdet kan vara mindre än det begärda antalet byte om antalet för närvarande tillgängliga byte är färre än det begärda antalet, eller så kan det vara 0 (noll) om slutet på strömmen har nåtts.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Läser asynkront en följd av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbrottsförfrågningar.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytearrayen att skriva de lästa byten till. |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på. |
| count | **int32_t** | Antalet byte att läsa. |

### Returvärde

Ett task-objekt som representerar den asynkrona läsoperationen. Värdet för TResult-parametern innehåller det totala antalet byte som lästs in i buffer. Resultatvärdet kan vara mindre än det begärda antalet byte om antalet för närvarande tillgängliga byte är färre än det begärda antalet, eller så kan det vara 0 (noll) om slutet på strömmen har nåtts.

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [CancellationToken](../../../system.threading/cancellationtoken/)
* Klass [Stream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: ReadAsync()
second_title: Aspose.Slides för C++ API-referens
description: Läser asynkront en sekvens av bytes från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa bytes och övervakar avbokningsförfrågningar.
type: docs
weight: 196
url: /sv/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metod

Läser asynkront en sekvens av bytes från den aktuella strömmen, flyttar positionen i strömmen framåt med antalet lästa bytes och övervakar avbokningsförfrågningar.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytearrayen att skriva de lästa byten till. |
| offset | **int32_t** | En nollbaserad position i **buffer** att börja skriva på. |
| count | **int32_t** | Antalet bytes att läsa. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Tokenet att övervaka för avbokningsförfrågningar. |

### Returvärde

En task som representerar den asynkrona läsoperationen. Värdet på TResult-parametern innehåller det totala antalet bytes som lästs in i bufferten. Resultatvärdet kan vara mindre än det begärda antalet bytes om antalet för närvarande tillgängliga bytes är mindre än det begärda, eller så kan det vara 0 (noll) om slutet på strömmen har nåtts.

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [CancellationToken](../../../system.threading/cancellationtoken/)
* Klass [FileStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)
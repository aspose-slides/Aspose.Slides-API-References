---
title: WriteAsync()
second_title: Aspose.Slides för C++ API-referens
description: Skriver asynkront en sekvens av byte till den aktuella strömmen, förflyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbokningsförfrågningar.
type: docs
weight: 66
url: /sv/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metod

Skriver asynkront en sekvens av byte till den aktuella strömmen, förflyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbokningsförfrågningar.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte som ska skrivas. |
| offset | **int32_t** | Ett nollbaserat index för elementet i **buffer** där delintervallet att skriva börjar. |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Tokenen som övervakas för avbokningsförfrågningar. |

### Returvärde

En uppgift som representerar den asynkrona skrivoperationen.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Skriver asynkront en sekvens av byte till den aktuella strömmen, förflyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbokningsförfrågningar.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte som ska skrivas. |
| offset | **int32_t** | Ett nollbaserat index för elementet i **buffer** där delintervallet att skriva börjar. |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas. |

### Returvärde

En uppgift som representerar den asynkrona skrivoperationen.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [CancellationToken](../../../system.threading/cancellationtoken/)
* Klass [Stream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)
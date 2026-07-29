---
title: WriteAsync()
second_title: Aspose.Slides för C++ API-referens
description: Skriver asynkront en sekvens av byte till den aktuella strömmen, flyttar den aktuella positionen i denna ström med antalet skrivna byte och övervakar avbrytningsförfrågningar.
type: docs
weight: 261
url: /sv/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metod

Skriver asynkront en sekvens av byte till den aktuella strömmen, flyttar den aktuella positionen i denna ström med antalet skrivna byte, och övervakar avbrytningsförfrågningar.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte som ska skrivas. |
| offset | **int32_t** | Ett 0-baserat index på elementet i **buffer** där delintervallet att skriva börjar. |
| count | **int32_t** | Antalet element i delintervallet som ska skrivas. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Tokenet som ska övervakas för avbrytningsförfrågningar. |

### Returvärde

En uppgift som representerar den asynkrona skrivoperationen.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [CancellationToken](../../../system.threading/cancellationtoken/)
* Klass [FileStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)
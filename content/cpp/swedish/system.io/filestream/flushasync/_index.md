---
title: FlushAsync()
second_title: Aspose.Slides för C++ API-referens
description: Rensar asynkront alla buffertar för detta flöde, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar.
type: docs
weight: 157
url: /sv/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) metod

Rensar asynkront alla buffertar för detta flöde, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Tokenet att övervaka för avbokningsförfrågningar. |

### Returvärde

En uppgift som representerar den asynkrona flush-operationen.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Klass [CancellationToken](../../../system.threading/cancellationtoken/)
* Klass [FileStream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)
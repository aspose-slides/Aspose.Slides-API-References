---
title: FlushAsync()
second_title: Aspose.Slides för C++ API-referens
description: Rensar asynkront alla buffertar för detta flöde, får eventuell buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar.
type: docs
weight: 118
url: /sv/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) metod

Rensar asynkront alla buffertar för detta flöde, får eventuell buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token som ska övervakas för avbokningsförfrågningar. |

### Returvärde

En task som representerar den asynkrona flush-operationen.

## Stream::FlushAsync() metod

Rensar asynkront alla buffertar för detta flöde, får eventuell buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### Returvärde

En task som representerar den asynkrona flush-operationen.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Klass [CancellationToken](../../../system.threading/cancellationtoken/)
* Klass [Stream](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)
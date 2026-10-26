---
title: FlushAsync()
second_title: Aspose.Slides für C++ API-Referenz
description: Löscht asynchron alle Puffer für diesen Stream, veranlasst, dass gepufferte Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen.
type: docs
weight: 118
url: /de/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) Methode


Löscht asynchron alle Puffer für diesen Stream, bewirkt, dass alle gepufferten Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Das Token, das auf Abbruchanforderungen überwacht wird. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Flush-Operation darstellt.

## Stream::FlushAsync() Methode


Löscht asynchron alle Puffer für diesen Stream, bewirkt, dass alle gepufferten Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### Rückgabewert

Eine Aufgabe, die die asynchrone Flush-Operation darstellt.

## Siehe auch

* Typedef [TaskPtr](../../../system/taskptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [Stream](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)
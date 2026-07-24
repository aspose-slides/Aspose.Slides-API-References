---
title: FlushAsync()
second_title: Aspose.Slides für C++ API-Referenz
description: Löscht asynchron alle Puffer für diesen Stream, veranlasst, dass alle gepufferten Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen.
type: docs
weight: 157
url: /de/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) Methode


Löscht asynchron alle Puffer für diesen Stream, veranlasst, dass alle gepufferten Daten in das zugrunde liegende Gerät geschrieben werden, und überwacht Abbruchanforderungen.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Das Token, das auf Abbruchanforderungen überwacht wird. |

### Rückgabewert

Eine Aufgabe, die die asynchrone Flush-Operation repräsentiert.

## Siehe auch

* Typedef [TaskPtr](../../../system/taskptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [FileStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)
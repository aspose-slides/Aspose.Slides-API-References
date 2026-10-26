---
title: FlushAsync()
second_title: Aspose.Slides C++ API referencia
description: Aszinkron módon törli a folyam összes puffert, az esetlegesen pufferelt adatokat az alatta lévő eszközre írja, és figyeli a leállítási kéréseket.
type: docs
weight: 157
url: /hu/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) metódus


Aszinkron módon törli a folyam összes puffert, az esetlegesen pufferelt adatokat az alatta lévő eszközre írja, és figyeli a leállítási kéréseket.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | A token a leállítási kérések figyelésére. |

### Visszatérési érték

Egy feladat, amely az aszinkron flush műveletet képviseli.

## Lásd még

* Typedef [TaskPtr](../../../system/taskptr/)
* Osztály [CancellationToken](../../../system.threading/cancellationtoken/)
* Osztály [FileStream](../)
* Névterület [System::IO](../../)
* Library [Aspose.Slides](../../../)
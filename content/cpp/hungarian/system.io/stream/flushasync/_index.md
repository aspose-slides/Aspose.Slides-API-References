---
title: FlushAsync()
second_title: Aspose.Slides C++ API referenciája
description: Aszinkron módon törli a stream összes puffert, az esetlegesen pufferelt adatokat az alatta lévő eszközre írja, és figyeli a leállítási kéréseket.
type: docs
weight: 118
url: /hu/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) metódus


Aszinkron módon törli a stream összes puffert, az esetlegesen pufferelt adatokat az alatta lévő eszközre írja, és figyeli a leállítási kéréseket.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | A token, amelyet a leállítási kérések figyelésére használnak. |

### Visszatérési érték

Egy feladat, amely a aszinkron flush műveletet képviseli.

## Stream::FlushAsync() metódus


Aszinkron módon törli a stream összes puffert, az esetlegesen pufferelt adatokat az alatta lévő eszközre írja, és figyeli a leállítási kéréseket.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### Visszatérési érték

Egy feladat, amely a aszinkron flush műveletet képviseli.

## Lásd még

* Typedef [TaskPtr](../../../system/taskptr/)
* Osztály [CancellationToken](../../../system.threading/cancellationtoken/)
* Osztály [Stream](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)
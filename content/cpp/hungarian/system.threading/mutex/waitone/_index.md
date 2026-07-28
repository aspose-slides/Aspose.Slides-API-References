---
title: WaitOne()
second_title: Aspose.Slides for C++ API referencia
description: Zárolja a mutexet. Szükség esetén korlátlan várakozást végez.
type: docs
weight: 53
url: /hu/system.threading/mutex/waitone/
---
## Mutex::WaitOne() metódus


Zárolja a mutexet. Szükség esetén korlátlan várakozást végez.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```


### Visszatérési érték

Mindig true értéket ad vissza, mivel nem tér vissza, amíg a mutex nincs zárolva.

## Mutex::WaitOne(int) metódus


Zárolja a mutexet. Szükség esetén várakozást végez.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| millisecondsTimeout | int | Várakozási időkorlát ezredmásodpercben. |

### Visszatérési érték

True értéket ad vissza, ha a mutex zárolva volt, vagy false értéket, ha a várakozási időt túllépték.

## Mutex::WaitOne(TimeSpan) metódus


Zárolja a mutexet. Szükség esetén várakozást végez.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/), amely a várandó ezredmásodpercek számát jelenti, vagy egy [System::TimeSpan](../../../system/timespan/), amely -1 ezredmásodpercet jelent, és végtelen ideig vár. |

### Visszatérési érték

True értéket ad vissza, ha a mutex zárolva volt, vagy false értéket, ha a várakozási időt túllépték.

## Lásd még

* Osztály [Mutex](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)
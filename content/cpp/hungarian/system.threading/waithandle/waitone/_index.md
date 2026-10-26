---
title: WaitOne()
second_title: Aspose.Slides C++ API hivatkozás
description: Vár a kezelő jelzésére korlátlan ideig.
type: docs
weight: 27
url: /hu/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() metódus


Vár a kezelő jelzésére korlátlan ideig.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### Visszatérési érték

Mindig true-t ad vissza, mivel nem fordul elő időtúllépés.

## WaitHandle::WaitOne(int) metódus


Vár a kezelő jelzésére.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) a várakozáshoz, ezredmásodpercben; a -1 végtelen várakozást jelent, a 0 ellenőrzés és visszatérés, a pozitív értékek időtúllépést jelentenek. |

### Visszatérési érték

True ha a kezelő aktiválódott, false ha az időtúllépés megtörtént.

## WaitHandle::WaitOne(TimeSpan) metódus


Vár a kezelő jelzésére.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | A [System::TimeSpan](../../../system/timespan/) a várandó ezredmásodperc számát jelenti, vagy egy [System::TimeSpan](../../../system/timespan/) amely -1 ezredmásodpercet jelent a határtalan várakozáshoz. |

### Visszatérési érték

True ha a kezelő aktiválódott, false ha az időtúllépés megtörtént.

## WaitHandle::WaitOne(int, bool) metódus


Vár a kezelő jelzésére.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) a várakozáshoz, ezredmásodpercben; a -1 végtelen várakozást jelent, a 0 ellenőrzés és visszatérés, a pozitív értékek időtúllépést jelentenek. |
| exitContext | **bool** | Ha true, a várakozás során le kell engedni a zárolást a kezelőn, mielőtt várakozik rá. |

### Visszatérési érték

True ha a kezelő aktiválódott, false ha az időtúllépés megtörtént.

## Lásd még

* Osztály [WaitHandle](../)
* Osztály [TimeSpan](../../../system/timespan/)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)
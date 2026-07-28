---
title: WaitAll()
second_title: Odwołanie API Aspose.Slides dla C++
description: Czeka, aż wszystkie uchwyty zostaną wyzwolone.
type: docs
weight: 1
url: /pl/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metoda

Czeka, aż wszystkie uchwyty zostaną wyzwolone.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Uchwyty do oczekiwania. |
| millisecondsTimeout | int | [Timeout](../../timeout/) do oczekiwania, w milisekundach; -1 oznacza nieskończone oczekiwanie, 0 oznacza sprawdź i zwróć, wartości dodatnie to limity czasu. |

### Wartość zwracana

True, jeśli wszystkie uchwyty zostały wyzwolone, false, jeśli przekroczono limit czasu.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metoda

Czeka, aż wszystkie uchwyty zostaną wyzwolone.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Uchwyty do oczekiwania. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) reprezentująca liczbę milisekund do oczekiwania lub [System::TimeSpan](../../../system/timespan/) reprezentująca -1 milisekund do nieograniczonego oczekiwania. |

### Wartość zwracana

True, jeśli wszystkie uchwyty zostały wyzwolone, false, jeśli przekroczono limit czasu.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metoda

Czeka, aż wszystkie uchwyty zostaną wyzwolone.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Uchwyty do oczekiwania. |

### Wartość zwracana

True, gdy każdy element w waitHandles otrzymał sygnał; w przeciwnym razie metoda nigdy nie zwraca.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
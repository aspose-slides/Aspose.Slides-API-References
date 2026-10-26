---
title: WaitAny()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Czeka, aż dowolny z uchwytów zostanie wyzwolony.
type: docs
weight: 14
url: /pl/system.threading/waithandle/waitany/
---
## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) metoda


Czeka, aż dowolny z uchwytów zostanie wyzwolony.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Uchwyty, na które należy czekać. |
| millisecondsTimeout | int | [Timeout](../../timeout/) do oczekiwania, w milisekundach; -1 oznacza nieskończone oczekiwanie, 0 oznacza sprawdź i zwróć, dodatnie wartości są limitami czasu. |

### Wartość zwracana

True jeśli którykolwiek uchwyt został wyzwolony, false jeśli przekroczono limit czasu.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) metoda


Czeka, aż dowolny z uchwytów zostanie wyzwolony.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Uchwyty, na które należy czekać. |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) reprezentuje liczbę milisekund do oczekiwania, lub [System::TimeSpan](../../../system/timespan/) reprezentuje -1 milisekund do nieskończonego oczekiwania. |

### Wartość zwracana

True jeśli którykolwiek uchwyt został wyzwolony, false jeśli przekroczono limit czasu.

## WaitHandle::WaitAny(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) metoda


Czeka, aż dowolny z uchwytów zostanie wyzwolony.

```cpp
static int System::Threading::WaitHandle::WaitAny(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Uchwyty, na które należy czekać. |

### Wartość zwracana

True, gdy każdy element w waitHandles otrzyma sygnał; w przeciwnym razie metoda nigdy nie zwraca.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [WaitHandle](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Threading](../../)
* Library [Aspose.Slides](../../../)
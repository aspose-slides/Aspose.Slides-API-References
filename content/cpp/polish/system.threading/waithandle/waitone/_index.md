---
title: WaitOne()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Czeka, aż uchwyt zostanie wyzwolony bez ograniczenia czasu.
type: docs
weight: 27
url: /pl/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() metoda

Czeka, aż uchwyt zostanie wyzwolony bez limitu czasu.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### Wartość zwracana

Zawsze zwraca true, ponieważ nie występuje limit czasu.

## WaitHandle::WaitOne(int) metoda

Czeka, aż uchwyt zostanie wyzwolony.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) do oczekiwania, w milisekundach; -1 oznacza nieskończone oczekiwanie, 0 oznacza sprawdzenie i zwrot, dodatnie wartości są limitami czasu. |

### Wartość zwracana

True, jeśli uchwyt został wyzwolony, false, jeśli limit czasu został przekroczony.

## WaitHandle::WaitOne(TimeSpan) metoda

Czeka, aż uchwyt zostanie wyzwolony.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) reprezentujący liczbę milisekund do oczekiwania lub [System::TimeSpan](../../../system/timespan/) reprezentujący -1 milisekund do oczekiwania w nieskończoność. |

### Wartość zwracana

True, jeśli uchwyt został wyzwolony, false, jeśli limit czasu został przekroczony.

## WaitHandle::WaitOne(int, bool) metoda

Czeka, aż uchwyt zostanie wyzwolony.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) do oczekiwania, w milisekundach; -1 oznacza nieskończone oczekiwanie, 0 oznacza sprawdzenie i zwrot, dodatnie wartości są limitami czasu. |
| exitContext | **bool** | Jeśli true, oczekiwanie powinno zwolnić blokadę na uchwycie przed jego oczekiwaniem. |

### Wartość zwracana

True, jeśli uchwyt został wyzwolony, false, jeśli limit czasu został przekroczony.

## Zobacz także

* Klasa [WaitHandle](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)
---
title: WaitOne()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Blokuje mutex. Wykonuje nieograniczone oczekiwanie, jeśli jest to konieczne.
type: docs
weight: 53
url: /pl/system.threading/mutex/waitone/
---
## Mutex::WaitOne() metoda

Blokuje mutex. Wykonuje nieograniczone oczekiwanie, jeśli jest to konieczne.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Wartość zwracana

Zawsze zwraca true, ponieważ nie zwraca, dopóki mutex nie zostanie zablokowany.

## Mutex::WaitOne(int) metoda

Blokuje mutex. Wykonuje oczekiwanie, jeśli jest to konieczne.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| millisecondsTimeout | int | Limit czasu oczekiwania w milisekundach. |

### Wartość zwracana

Zwraca true, jeśli mutex został zablokowany, lub false, jeśli przekroczono limit czasu.

## Mutex::WaitOne(TimeSpan) metoda

Blokuje mutex. Wykonuje oczekiwanie, jeśli jest to konieczne.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | [System::TimeSpan](../../../system/timespan/) reprezentujący liczbę milisekund do oczekiwania, lub [System::TimeSpan](../../../system/timespan/) reprezentujący -1 milisekund, aby czekać w nieskończoność. |

### Wartość zwracana

Zwraca true, jeśli mutex został zablokowany, lub false, jeśli przekroczono limit czasu.

## Zobacz także

* Klasa [Mutex](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)
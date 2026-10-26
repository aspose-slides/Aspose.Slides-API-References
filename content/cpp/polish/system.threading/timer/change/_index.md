---
title: Change()
second_title: Aspose.Slides dla C++ – referencja API
description: Ponownie planuje lub anuluje timer.
type: docs
weight: 14
url: /pl/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) metoda


Ponownie planuje lub anuluje timer.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) przed następnym wywołaniem funkcji zwrotnej, w milisekundach; ujemne wartości anulują timer, nawet jeśli został zaplanowany. |
| period | **int64_t** | [Timeout](../../timeout/) pomiędzy kolejnymi wywołaniami funkcji zwrotnej, w milisekundach; wartości nie-dodatnie oznaczają, że timer powinien być wykonany tylko raz. |

## Timer::Change(System::TimeSpan, System::TimeSpan) metoda


Ponownie planuje lub anuluje timer.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) przed następnym wywołaniem funkcji zwrotnej; ujemne wartości anulują timer, nawet jeśli został zaplanowany. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) pomiędzy kolejnymi wywołaniami funkcji zwrotnej; wartości nie-dodatnie oznaczają, że timer powinien być wykonany tylko raz. |

## Zobacz także

* Klasa [Timer](../)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)
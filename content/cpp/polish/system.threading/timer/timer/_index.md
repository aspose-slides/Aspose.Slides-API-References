---
title: Timer()
second_title: Aspose.Slides dla C++ – odwołanie do API
description: Konstruktor.
type: docs
weight: 1
url: /pl/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) konstruktor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funkcja wywoływana przez timer. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) konstruktor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funkcja wywoływana przez timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument funkcji zwrotnej. |
| dueTime | **int64_t** | [Timeout](../../timeout/) przed pierwszym wywołaniem funkcji zwrotnej, w milisekundach; ujemne wartości nie planują timera po utworzeniu, więc może być później ponownie zaplanowany. |
| period | **int64_t** | [Timeout](../../timeout/) pomiędzy kolejnymi wywołaniami funkcji zwrotnej, w milisekundach; nie dodatnie wartości oznaczają, że timer ma być wykonany tylko raz. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) konstruktor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funkcja wywoływana przez timer. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument funkcji zwrotnej. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) przed pierwszym wywołaniem funkcji zwrotnej; ujemne wartości nie planują timera po utworzeniu, więc może być później ponownie zaplanowany. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) pomiędzy kolejnymi wywołaniami funkcji zwrotnej; nie dodatnie wartości oznaczają, że timer ma być wykonany tylko raz. |

## Zobacz również

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Timer](../)
* Klasa [Object](../../../system/object/)
* Klasa [TimeSpan](../../../system/timespan/)
* Przestrzeń nazw [System::Threading](../../)
* Library [Aspose.Slides](../../../)
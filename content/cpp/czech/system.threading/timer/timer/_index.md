---
title: Timer()
second_title: Aspose.Slides pro C++ API Reference
description: Konstruktor.
type: docs
weight: 1
url: /cs/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) konstruktor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funkce, která má být volána časovačem. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) konstruktor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funkce, která má být volána časovačem. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument funkce zpětného volání. |
| dueTime | **int64_t** | [Timeout](../../timeout/) před první výzvou funkce zpětného volání, v milisekundách; záporné hodnoty neplánují časovač po vytvoření, takže jej lze naplánovat později. |
| period | **int64_t** | [Timeout](../../timeout/) mezi po sobě jdoucími voláními funkce zpětného volání, v milisekundách; nekladné hodnoty znamenají, že časovač má být proveden pouze jednou. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) konstruktor


Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funkce, která má být volána časovačem. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument funkce zpětného volání. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) před první výzvou funkce zpětného volání; záporné hodnoty neplánují časovač po vytvoření, takže jej lze naplánovat později. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) mezi po sobě jdoucími voláními funkce zpětného volání; nekladné hodnoty znamenají, že časovač má být proveden pouze jednou. |

## Viz také

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Timer](../)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
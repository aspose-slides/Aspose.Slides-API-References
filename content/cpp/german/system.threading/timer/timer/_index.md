---
title: Timer()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruktor.
type: docs
weight: 1
url: /de/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) Konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funktion, die vom Timer aufgerufen wird. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) Konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funktion, die vom Timer aufgerufen wird. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument der Callback-Funktion. |
| dueTime | **int64_t** | [Timeout](../../timeout/) vor dem ersten Aufruf der Callback-Funktion, in Millisekunden; negative Werte planen den Timer nach der Erstellung nicht ein, sodass er später neu geplant werden kann. |
| period | **int64_t** | [Timeout](../../timeout/) zwischen aufeinanderfolgenden Aufrufen der Callback-Funktion, in Millisekunden; nicht-positive Werte bedeuten, dass der Timer nur einmal ausgeführt werden soll. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) Konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funktion, die vom Timer aufgerufen wird. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument der Callback-Funktion. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) vor dem ersten Aufruf der Callback-Funktion; negative Werte planen den Timer nach der Erstellung nicht ein, sodass er später neu geplant werden kann. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) zwischen aufeinanderfolgenden Aufrufen der Callback-Funktion; nicht-positive Werte bedeuten, dass der Timer nur einmal ausgeführt werden soll. |

## Siehe auch

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Timer](../)
* Klasse [Object](../../../system/object/)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)
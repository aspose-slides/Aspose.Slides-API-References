---
title: Change()
second_title: Aspose.Slides für C++ API-Referenz
description: Plant den Timer neu oder bricht ihn ab.
type: docs
weight: 14
url: /de/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) Methode


Plant den Timer neu oder bricht ihn ab.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) vor dem nächsten Aufruf der Callback-Funktion, in Millisekunden; negative Werte brechen den Timer ab, selbst wenn er geplant war. |
| period | **int64_t** | [Timeout](../../timeout/) zwischen aufeinanderfolgenden Aufrufen der Callback-Funktion, in Millisekunden; nicht-positive Werte bedeuten, dass der Timer nur einmal ausgeführt werden soll. |

## Timer::Change(System::TimeSpan, System::TimeSpan) Methode


Plant den Timer neu oder bricht ihn ab.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) vor dem nächsten Aufruf der Callback-Funktion; negative Werte brechen den Timer ab, selbst wenn er geplant war. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) zwischen aufeinanderfolgenden Aufrufen der Callback-Funktion; nicht-positive Werte bedeuten, dass der Timer nur einmal ausgeführt werden soll. |

## Siehe auch

* Klasse [Timer](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)
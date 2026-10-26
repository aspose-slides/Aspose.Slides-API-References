---
title: Change()
second_title: Aspose.Slides pro C++ API Reference
description: Znovu naplánuje nebo zruší časovač.
type: docs
weight: 14
url: /cs/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) metoda

Znovu naplánuje nebo zruší časovač.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### Parametry

| Parametr | Typ | Popis |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) před dalším vyvoláním funkce zpětného volání, v milisekundách; záporné hodnoty zruší časovač, i když byl naplánován. |
| period | **int64_t** | [Timeout](../../timeout/) mezi po sobě jdoucími vyvoláními funkce zpětného volání, v milisekundách; nekladné hodnoty znamenají, že časovač má být proveden pouze jednou. |

## Timer::Change(System::TimeSpan, System::TimeSpan) metoda

Znovu naplánuje nebo zruší časovač.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### Parametry

| Parametr | Typ | Popis |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) před dalším vyvoláním funkce zpětného volání; záporné hodnoty zruší časovač, i když byl naplánován. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) mezi po sobě jdoucími vyvoláními funkce zpětného volání; nekladné hodnoty znamenají, že časovač má být proveden pouze jednou. |

## Viz také

* Třída [Timer](../)
* Třída [TimeSpan](../../../system/timespan/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)
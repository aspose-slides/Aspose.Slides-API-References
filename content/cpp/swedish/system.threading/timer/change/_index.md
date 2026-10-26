---
title: Change()
second_title: Aspose.Slides för C++ API-referens
description: Schemalägger om eller avbryter timern.
type: docs
weight: 14
url: /sv/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) metod

Schemalägger om eller avbryter timern.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) innan nästa anrop av callback-funktionen, i millisekunder; negativa värden avbryter timern även om den var schemalagd. |
| period | **int64_t** | [Timeout](../../timeout/) mellan på varandra följande anrop av callback-funktionen, i millisekunder; icke-positiva värden betyder att timern bara ska köras en gång. |

## Timer::Change(System::TimeSpan, System::TimeSpan) metod

Schemalägger om eller avbryter timern.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) innan nästa anrop av callback-funktionen; negativa värden avbryter timern även om den var schemalagd. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) mellan på varandra följande anrop av callback-funktionen; icke-positiva värden betyder att timern bara ska köras en gång. |

## Se även

* Klass [Timer](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)
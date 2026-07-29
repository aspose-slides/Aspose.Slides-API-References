---
title: Timer()
second_title: Aspose.Slides för C++ API-referens
description: Konstruktor.
type: docs
weight: 1
url: /sv/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funktion som ska anropas av timern. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funktion som ska anropas av timern. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument till återanropsfunktionen. |
| dueTime | **int64_t** | [Timeout](../../timeout/) före första anrop av återanropsfunktionen, i millisekunder; negativa värden schemalägger inte timern efter skapandet så den kan schemaläggas om senare. |
| period | **int64_t** | [Timeout](../../timeout/) mellan på varandra följande anrop av återanropsfunktionen, i millisekunder; icke-positiva värden betyder att timern bara ska köras en gång. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) konstruktor

Konstruktor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Funktion som ska anropas av timern. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument till återanropsfunktionen. |
| dueTime | [System::TimeSpan](../../../system/timespan/) [Timeout](../../timeout/) före första anrop av återanropsfunktionen; negativa värden schemalägger inte timern efter skapandet så den kan schemaläggas om senare. |
| period | [System::TimeSpan](../../../system/timespan/) [Timeout](../../timeout/) mellan på varandra följande anrop av återanropsfunktionen; icke-positiva värden betyder att timern bara ska köras en gång. |

## Se även

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Timer](../)
* Klass [Object](../../../system/object/)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)
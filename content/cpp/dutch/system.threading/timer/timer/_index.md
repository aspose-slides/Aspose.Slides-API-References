---
title: Timer()
second_title: Aspose.Slides voor C++ API-referentie
description: Constructor.
type: docs
weight: 1
url: /nl/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructor

Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Functie die door de timer wordt aangeroepen. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructor

Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Functie die door de timer wordt aangeroepen. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument van de callback-functie. |
| dueTime | **int64_t** | [Timeout](../../timeout/) vóór de eerste aanroep van de callback-functie, in milliseconden; negatieve waarden plannen de timer niet na creatie, zodat deze later opnieuw kan worden ingepland. |
| period | **int64_t** | [Timeout](../../timeout/) tussen opeenvolgende aanroepen van de callback-functie, in milliseconden; niet-positieve waarden betekenen dat de timer slechts één keer moet worden uitgevoerd. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructor

Constructor.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Functie die door de timer wordt aangeroepen. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument van de callback-functie. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) vóór de eerste aanroep van de callback-functie; negatieve waarden plannen de timer niet na creatie, zodat deze later opnieuw kan worden ingepland. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) tussen opeenvolgende aanroepen van de callback-functie; niet-positieve waarden betekenen dat de timer slechts één keer moet worden uitgevoerd. |

## Zie ook

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Timer](../)
* Class [Object](../../../system/object/)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)
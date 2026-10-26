---
title: Change()
second_title: Aspose.Slides voor C++ API-referentie
description: Plant de timer opnieuw in of annuleert deze.
type: docs
weight: 14
url: /nl/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) methode


Plant de timer opnieuw in of annuleert deze.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) vóór de volgende aanroep van de callback-functie, in milliseconden; negatieve waarden annuleren de timer zelfs als deze was gepland. |
| period | **int64_t** | [Timeout](../../timeout/) tussen opeenvolgende aanroepen van de callback-functie, in milliseconden; niet-positieve waarden betekenen dat de timer slechts één keer moet worden uitgevoerd. |

## Timer::Change(System::TimeSpan, System::TimeSpan) methode


Plant de timer opnieuw in of annuleert deze.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) vóór de volgende aanroep van de callback-functie; negatieve waarden annuleren de timer zelfs als deze was gepland. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) tussen opeenvolgende aanroepen van de callback-functie; niet-positieve waarden betekenen dat de timer slechts één keer moet worden uitgevoerd. |

## Zie ook

* Klasse [Timer](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)
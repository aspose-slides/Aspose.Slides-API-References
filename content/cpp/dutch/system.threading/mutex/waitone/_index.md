---
title: WaitOne()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergrendelt mutex. Voert onbeperkt wachten uit indien nodig.
type: docs
weight: 53
url: /nl/system.threading/mutex/waitone/
---
## Mutex::WaitOne() methode

Vergrendelt mutex. Voert onbeperkt wachten uit indien nodig.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Retourwaarde

Retourneert altijd true omdat het niet terugkeert totdat mutex vergrendeld is.

## Mutex::WaitOne(int) methode

Vergrendelt mutex. Voert wachten uit indien nodig.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| millisecondsTimeout | int | Wachttijd in milliseconden. |

### Retourwaarde

Retourneert true als mutex vergrendeld is of false als de time-out is overschreden.

## Mutex::WaitOne(TimeSpan) methode

Vergrendelt mutex. Voert wachten uit indien nodig.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Een [System::TimeSpan](../../../system/timespan/) die het aantal milliseconden dat gewacht moet worden vertegenwoordigt, of een [System::TimeSpan](../../../system/timespan/) die -1 milliseconden betekent om onbeperkt te wachten. |

### Retourwaarde

Retourneert true als mutex vergrendeld is of false als de time-out is overschreden.

## Zie ook

* Klasse [Mutex](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Naamruimte [System::Threading](../../)
* Library [Aspose.Slides](../../../)
---
title: Join()
second_title: Aspose.Slides voor C++ API-referentie
description: Koppelt beheerde thread. Voert onbeperkt wachten uit indien vereist.
type: docs
weight: 196
url: /nl/system.threading/thread/join/
---
## Thread::Join() methode


Koppelt beheerde thread. Voert onbeperkt wachten uit indien vereist.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) methode


Koppelt beheerde thread. Voert beperkt wachten uit.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| millisecondsTimeout | int | Wachttime-out in milliseconden. |

### Retourwaarde

True als de thread succesvol is gekoppeld, false als de time-out is overschreden.

## Thread::Join(TimeSpan) methode


Koppelt beheerde thread. Voert beperkt wachten uit.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Een [TimeSpan](../../../system/timespan/) ingesteld op de hoeveelheid tijd om te wachten tot de thread wordt beëindigd. |

### Retourwaarde

True als de thread succesvol is gekoppeld, false als de time-out is overschreden.

## Zie ook

* Klasse [Thread](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)
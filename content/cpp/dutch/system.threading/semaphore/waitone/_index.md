---
title: WaitOne()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergrendelt de semaphore. Voert onbeperkt wachten uit indien nodig.
type: docs
weight: 40
url: /nl/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() methode

Vergrendelt de semaphore. Voert onbeperkt wachten uit indien nodig.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### Retourwaarde

Geeft altijd true terug, omdat het niet terugkeert totdat de semaphore vergrendeld is.

## Semaphore::WaitOne(int) methode

Vergrendelt de semaphore. Voert wacht uit indien nodig.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| millisecondsTimeout | int | Wachttijd in milliseconden. |

### Retourwaarde

Retourneert true als de semaphore vergrendeld was of false als de time-out is overschreden.

## Zie ook

* Klasse [Semaphore](../)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)
---
title: WaitOne()
second_title: Aspose.Slides für C++ API Referenz
description: Sperrt das Semaphore. Führt unbegrenztes Warten aus, falls notwendig.
type: docs
weight: 40
url: /de/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() Methode

Sperrt das Semaphore. Führt unbegrenztes Warten aus, falls notwendig.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### Rückgabewert

Gibt immer true zurück, da es nicht zurückkehrt, bis das Semaphore gesperrt ist.

## Semaphore::WaitOne(int) Methode

Sperrt das Semaphore. Führt Warten aus, falls notwendig.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsTimeout | int | Wartezeitüberschreitung in Millisekunden. |

### Rückgabewert

Gibt true zurück, wenn das Semaphore gesperrt war, oder false, wenn das Zeitlimit überschritten wurde.

## Siehe auch

* Klasse [Semaphore](../)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)
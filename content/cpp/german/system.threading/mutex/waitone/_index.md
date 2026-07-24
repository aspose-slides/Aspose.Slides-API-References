---
title: WaitOne()
second_title: Aspose.Slides für C++ API-Referenz
description: Sperrt das Mutex. Führt bei Bedarf unbegrenztes Warten aus.
type: docs
weight: 53
url: /de/system.threading/mutex/waitone/
---
## Mutex::WaitOne() Methode

Sperrt das Mutex. Führt bei Bedarf unbegrenztes Warten aus.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Rückgabewert

Gibt immer true zurück, da es nicht zurückkehrt, bis das Mutex gesperrt ist.

## Mutex::WaitOne(int) Methode

Sperrt das Mutex. Führt bei Bedarf ein Warten aus.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsTimeout | int | Warte-Timeout in Millisekunden. |

### Rückgabewert

Gibt true zurück, wenn das Mutex gesperrt war, oder false, wenn das Timeout überschritten wurde.

## Mutex::WaitOne(TimeSpan) Methode

Sperrt das Mutex. Führt bei Bedarf ein Warten aus.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Ein [System::TimeSpan](../../../system/timespan/), das die Anzahl der Millisekunden zum Warten darstellt, oder ein [System::TimeSpan](../../../system/timespan/), das -1 Millisekunden für unbegrenztes Warten darstellt. |

### Rückgabewert

Gibt true zurück, wenn das Mutex gesperrt war, oder false, wenn das Timeout überschritten wurde.

## Siehe auch

* Klasse [Mutex](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)
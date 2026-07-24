---
title: Join()
second_title: Aspose.Slides für C++ API-Referenz
description: Tritt dem verwalteten Thread bei. Führt unbegrenztes Warten aus, falls erforderlich.
type: docs
weight: 196
url: /de/system.threading/thread/join/
---
## Thread::Join() Methode

Tritt dem verwalteten Thread bei. Führt unbegrenztes Warten aus, falls erforderlich.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) Methode

Tritt dem verwalteten Thread bei. Führt begrenztes Warten aus.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsTimeout | int | Wartenzeitlimit in Millisekunden. |

### Rückgabewert

True, wenn der Thread erfolgreich beigetreten wurde, false, wenn das Zeitlimit überschritten wurde.

## Thread::Join(TimeSpan) Methode

Tritt dem verwalteten Thread bei. Führt begrenztes Warten aus.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Ein [TimeSpan](../../../system/timespan/), der auf die Dauer eingestellt ist, die gewartet werden soll, bis der Thread beendet ist. |

### Rückgabewert

True, wenn der Thread erfolgreich beigetreten wurde, false, wenn das Zeitlimit überschritten wurde.

## Siehe auch

* Klasse [Thread](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)
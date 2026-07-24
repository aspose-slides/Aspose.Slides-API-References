---
title: WaitOne()
second_title: Aspose.Slides für C++ API-Referenz
description: Wartet, bis das Handle unbegrenzt ausgelöst wird.
type: docs
weight: 27
url: /de/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() method

Wartet, bis das Handle unbegrenzt ausgelöst wird.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### Rückgabewert

Gibt immer true zurück, da kein Timeout auftritt.

## WaitHandle::WaitOne(int) method

Wartet, bis das Handle ausgelöst wird.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) zu warten, in Millisekunden; -1 bedeutet unbegrenztes Warten, 0 bedeutet prüfen-und-zurückkehren, positive Werte sind Timeouts. |

### Rückgabewert

True, wenn das Handle ausgelöst wurde, false, wenn das Timeout überschritten wurde.

## WaitHandle::WaitOne(TimeSpan) method

Wartet, bis das Handle ausgelöst wird.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Ein [System::TimeSpan](../../../system/timespan/), das die Anzahl der Millisekunden darstellt, die gewartet werden sollen, oder ein [System::TimeSpan](../../../system/timespan/), das -1 Millisekunden für unbegrenztes Warten darstellt. |

### Rückgabewert

True, wenn das Handle ausgelöst wurde, false, wenn das Timeout überschritten wurde.

## WaitHandle::WaitOne(int, bool) method

Wartet, bis das Handle ausgelöst wird.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) zu warten, in Millisekunden; -1 bedeutet unbegrenztes Warten, 0 bedeutet prüfen-und-zurückkehren, positive Werte sind Timeouts. |
| exitContext | **bool** | Wenn true, sollte das Warten die Sperre des Handles vor dem Warten freigeben. |

### Rückgabewert

True, wenn das Handle ausgelöst wurde, false, wenn das Timeout überschritten wurde.

## Siehe auch

* Klasse [WaitHandle](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)
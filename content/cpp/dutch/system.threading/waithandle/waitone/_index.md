---
title: WaitOne()
second_title: Aspose.Slides voor C++ API-referentie
description: Wacht tot de handle afvuurt voor onbeperkte periode.
type: docs
weight: 27
url: /nl/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() method


Wacht tot de handle afvuurt voor onbeperkte periode.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```


### Returnwaarde

Geeft altijd true terug omdat er geen time-out optreedt.

## WaitHandle::WaitOne(int) method


Wacht tot de handle afvuurt.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) om te wachten, in milliseconden; -1 betekent oneindig wachten, 0 betekent controleer-en-keer-terug, positieve waarden zijn time-outs. |

### Returnwaarde

True if handle fired, false if timeout exceeded.

## WaitHandle::WaitOne(TimeSpan) method


Wacht tot de handle afvuurt.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Een [System::TimeSpan](../../../system/timespan/) die het aantal milliseconden aangeeft om te wachten, of een [System::TimeSpan](../../../system/timespan/) die -1 milliseconden aangeeft voor oneindig wachten. |

### Returnwaarde

True if handle fired, false if timeout exceeded.

## WaitHandle::WaitOne(int, bool) method


Wacht tot de handle afvuurt.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) om te wachten, in milliseconden; -1 betekent oneindig wachten, 0 betekent controleer-en-keer-terug, positieve waarden zijn time-outs. |
| exitContext | **bool** | Als true, moet het wachten de lock op de handle laten vallen voordat er gewacht wordt. |

### Returnwaarde

True if handle fired, false if timeout exceeded.

## Zie ook

* Klasse [WaitHandle](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Naamruimte [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)
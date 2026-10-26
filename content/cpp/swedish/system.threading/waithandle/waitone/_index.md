---
title: WaitOne()
second_title: Aspose.Slides för C++ API-referens
description: Väntar på att handtaget ska avfyras under obegränsad period.
type: docs
weight: 27
url: /sv/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() metod

Väntar på att handtaget ska avfyras under obegränsad period.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### Returvärde

Returnerar alltid true eftersom ingen tidsgräns inträffar.

## WaitHandle::WaitOne(int) metod

Väntar på att handtaget ska avfyras.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) att vänta på, i millisekunder; -1 betyder oändlig väntan, 0 betyder kontroll-och-retur, positiva värden är tidsgränser. |

### Returvärde

True om handtaget avfyras, false om tidsgränsen överskrids.

## WaitHandle::WaitOne(TimeSpan) metod

Väntar på att handtaget ska avfyras.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | En [System::TimeSpan](../../../system/timespan/) som representerar antalet millisekunder att vänta, eller en [System::TimeSpan](../../../system/timespan/) som representerar -1 millisekunder för att vänta på obestämd tid. |

### Returvärde

True om handtaget avfyras, false om tidsgränsen överskrids.

## WaitHandle::WaitOne(int, bool) metod

Väntar på att handtaget ska avfyras.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) att vänta på, i millisekunder; -1 betyder oändlig väntan, 0 betyder kontroll-och-retur, positiva värden är tidsgränser. |
| exitContext | **bool** | Om true bör väntan släppa låset på handtaget innan det väntas på. |

### Returvärde

True om handtaget avfyras, false om tidsgränsen överskrids.

## Se också

* Klass [WaitHandle](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)
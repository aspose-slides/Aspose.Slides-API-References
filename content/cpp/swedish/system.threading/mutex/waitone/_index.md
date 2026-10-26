---
title: WaitOne()
second_title: Aspose.Slides för C++ API-referens
description: Låser mutex. Utför obegränsad väntan om nödvändigt.
type: docs
weight: 53
url: /sv/system.threading/mutex/waitone/
---
## Mutex::WaitOne() metod

Låser mutex. Utför obegränsad väntan om nödvändigt.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Returvärde

Returnerar alltid true eftersom den inte återgår förrän mutex är låst.

## Mutex::WaitOne(int) metod

Låser mutex. Utför väntan om nödvändigt.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | Väntningstimeout i millisekunder. |

### Returvärde

Returnerar true om mutex låstes eller false om timeout överskreds.

## Mutex::WaitOne(TimeSpan) metod

Låser mutex. Utför väntan om nödvändigt.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Ett [System::TimeSpan](../../../system/timespan/) som representerar antalet millisekunder att vänta, eller ett [System::TimeSpan](../../../system/timespan/) som representerar -1 millisekunder för att vänta på obestämd tid. |

### Returvärde

Returnerar true om mutex låstes eller false om timeout överskreds.

## Se även

* Klass [Mutex](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)
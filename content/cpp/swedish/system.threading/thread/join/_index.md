---
title: Join()
second_title: Aspose.Slides för C++ API-referens
description: Sätter ihop hanterad tråd. Utför obegränsad väntan om det krävs.
type: docs
weight: 196
url: /sv/system.threading/thread/join/
---
## Thread::Join() method

Sätter ihop hanterad tråd. Utför obegränsad väntan om det krävs.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) method

Sätter ihop hanterad tråd. Utför begränsad väntan.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | Väntetidsgräns i millisekunder. |

### Returvärde

True om tråden framgångsrikt anslöts, false om tidsgränsen överskreds.

## Thread::Join(TimeSpan) method

Sätter ihop hanterad tråd. Utför begränsad väntan.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | En [TimeSpan](../../../system/timespan/) inställd på den tid tråden ska vänta på att avslutas. |

### Returvärde

True om tråden framgångsrikt anslöts, false om tidsgränsen överskreds.

## Se även

* Klass [Thread](../)
* Klass [TimeSpan](../../../system/timespan/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)
---
title: Equals()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det angivna objektet.
type: docs
weight: 40
url: /sv/system/timespan/equals/
---
## TimeSpan::Equals(TimeSpan) const metod

Bestämmer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det angivna objektet.

```cpp
constexpr bool System::TimeSpan::Equals(TimeSpan value) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TimeSpan](../) | The [TimeSpan](../) object to compare the current object with |

### Returvärde

True if the current object and the specified object represent the same time interval, otherwise - false

## TimeSpan::Equals(const SharedPtr\<Object\>\&) const metod

Bestämmer om tidsintervallet som representeras av det aktuella objektet är lika med tidsintervallet som representeras av det angivna objektet.

```cpp
bool System::TimeSpan::Equals(const SharedPtr<Object> &obj) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The [TimeSpan](../) object to compare the current object with |

### Returvärde

True if the current object and the specified object represent the same time interval, otherwise - false

## TimeSpan::Equals(TimeSpan, TimeSpan) metod

Returnerar true om de angivna objekten representerar samma tidsintervall, annars - false.

```cpp
static constexpr bool System::TimeSpan::Equals(TimeSpan a, TimeSpan b)
```

## Se också

* Typedef [SharedPtr](../../sharedptr/)
* Klass [TimeSpan](../)
* Klass [Object](../../object/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
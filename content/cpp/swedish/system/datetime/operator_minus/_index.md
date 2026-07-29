---
title: operator-()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en ny instans av DateTime-klassen som representerar datum- och tidsvärdet som är resultatet av subtraktionen av det angivna tidsintervallet från värdet som representeras av det aktuella objektet.
type: docs
weight: 651
url: /sv/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const metod


Returns a new instance of the [DateTime](../) klass representing the date and time value which is the result of subtraction of the specified time span from the value represented by the current object.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Ett tidsintervall att subtrahera |

### Returvärde

A new instance of the [DateTime](../) klass representing the date and time value which is the result of subtraction of **value** from the value represented by the current object.

## DateTime::operator-(DateTime) const metod


Returns an instance of [TimeSpan](../../timespan/) klass that represents the time interval between the date and time values represented by the current and the specified objects.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../) | En instans av [DateTime](../) klass som markerar ena änden av intervallet som ska beräknas |

### Returvärde

En instans av [TimeSpan](../../timespan/) klass som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella objektet och **value**.

## Se även

* Klass [DateTime](../)
* Klass [TimeSpan](../../timespan/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
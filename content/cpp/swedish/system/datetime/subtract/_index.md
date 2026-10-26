---
title: Subtract()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en ny instans av klassen DateTime som representerar datum- och tidsvärdet som är resultatet av subtraktionen av det angivna tidsintervallet från värdet som representeras av det aktuella objektet.
type: docs
weight: 326
url: /sv/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const metod


Returnerar en ny instans av klassen [DateTime](../) som representerar datum- och tidsvärdet som är resultatet av subtraktionen av den angivna tidsintervallet från värdet som representeras av det aktuella objektet.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Ett tidsintervall att subtrahera |

### Returvärde

En ny instans av klassen [DateTime](../) som representerar datum- och tidsvärdet som är resultatet av subtraktionen av **duration** från värdet som representeras av det aktuella objektet.

## DateTime::Subtract(DateTime) const metod


Returnerar en instans av klassen [TimeSpan](../../timespan/) som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella och det angivna objektet.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| value | [DateTime](../) | En instans av klassen [DateTime](../) som markerar en ände av intervallet som ska beräknas |

### Returvärde

En instans av klassen [TimeSpan](../../timespan/) som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella objektet och **value**.

## Se också

* Klass [DateTime](../)
* Klass [TimeSpan](../../timespan/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
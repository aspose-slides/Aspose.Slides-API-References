---
title: operator-()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en ny instans av DateTimeOffset-klassen som representerar datum- och tidsvärdet som är resultatet av subtraktion av det angivna tidsintervallet från värdet som representeras av det aktuella objektet.
type: docs
weight: 521
url: /sv/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const metod

Returnerar en ny instans av klassen [DateTimeOffset](../) som representerar datum- och tidsvärdet som är resultatet av subtraktion av det angivna tidsintervallet från värdet som representeras av det aktuella objektet.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Ett tidsintervall att subtrahera |

### Returvärde

En ny instans av klassen [DateTimeOffset](../) som representerar datum- och tidsvärdet som är resultatet av subtraktion av **value** från värdet som representeras av det aktuella objektet.

## DateTimeOffset::operator-(const DateTimeOffset\&) const metod

Returnerar en instans av klassen [TimeSpan](../../timespan/) som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella och det angivna objektet.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | En instans av klassen [DateTime](../../datetime/) som markerar den ena änden av intervallet som ska beräknas |

### Returvärde

En instans av klassen [TimeSpan](../../timespan/) som representerar tidsintervallet mellan datum- och tidsvärdena som representeras av det aktuella objektet och **other**.

## Se även

* Klass [DateTimeOffset](../)
* Klass [TimeSpan](../../timespan/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)
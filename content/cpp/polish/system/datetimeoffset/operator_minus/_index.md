---
title: operator-()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca nową instancję klasy DateTimeOffset reprezentującą wartość daty i czasu, która jest wynikiem odjęcia określonego przedziału czasu od wartości reprezentowanej przez bieżący obiekt.
type: docs
weight: 521
url: /pl/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const metoda


Zwraca nową instancję klasy [DateTimeOffset](../), reprezentującą wartość daty i czasu, która jest wynikiem odjęcia określonego przedziału czasu od wartości reprezentowanej przez bieżący obiekt.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Przedział czasu do odjęcia |

### Wartość zwracana

Nowa instancja klasy [DateTimeOffset](../), reprezentująca wartość daty i czasu, która jest wynikiem odjęcia **value** od wartości reprezentowanej przez bieżący obiekt.

## DateTimeOffset::operator-(const DateTimeOffset\&) const metoda


Zwraca instancję klasy [TimeSpan](../../timespan/), która reprezentuje przedział czasu pomiędzy wartościami daty i czasu reprezentowanymi przez bieżący i określony obiekt.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Instancja klasy [DateTime](../../datetime/), która oznacza jeden koniec przedziału do obliczenia |

### Wartość zwracana

Instancja klasy [TimeSpan](../../timespan/), reprezentująca przedział czasu pomiędzy wartościami daty i czasu reprezentowanymi przez bieżący obiekt i **other**.

## Zobacz także

* Klasa [DateTimeOffset](../)
* Klasa [TimeSpan](../../timespan/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)
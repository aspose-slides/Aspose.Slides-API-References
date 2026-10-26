---
title: operator-()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca nową instancję klasy DateTime reprezentującą wartość daty i czasu, będącą wynikiem odjęcia określonego przedziału czasu od wartości reprezentowanej przez bieżący obiekt.
type: docs
weight: 651
url: /pl/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const metoda

Zwraca nową instancję klasy [DateTime](../) reprezentującą wartość daty i czasu, która jest wynikiem odjęcia określonego przedziału czasu od wartości reprezentowanej przez bieżący obiekt.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Przedział czasu do odjęcia |

### Wartość zwracana

Nowa instancja klasy [DateTime](../) reprezentująca wartość daty i czasu, która jest wynikiem odjęcia **value** od wartości reprezentowanej przez bieżący obiekt.

## DateTime::operator-(DateTime) const metoda

Zwraca instancję klasy [TimeSpan](../../timespan/) reprezentującą przedział czasu pomiędzy wartościami daty i czasu reprezentowanymi przez bieżący i określony obiekt.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [DateTime](../) | Instancja klasy [DateTime](../) oznaczająca jeden koniec przedziału, który ma zostać obliczony |

### Wartość zwracana

Instancja klasy [TimeSpan](../../timespan/) reprezentująca przedział czasu pomiędzy wartościami daty i czasu reprezentowanymi przez bieżący obiekt oraz **value**.

## Zobacz także

* Klasa [DateTime](../)
* Klasa [TimeSpan](../../timespan/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)
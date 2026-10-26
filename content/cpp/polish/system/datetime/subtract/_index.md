---
title: Subtract()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Zwraca nową instancję klasy DateTime reprezentującą wartość daty i czasu, będącą wynikiem odjęcia określonego przedziału czasu od wartości reprezentowanej przez bieżący obiekt.
type: docs
weight: 326
url: /pl/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const metoda


Zwraca nową instancję klasy [DateTime](../) reprezentującą wartość daty i czasu, która jest wynikiem odjęcia określonego przedziału czasu od wartości reprezentowanej przez bieżący obiekt.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Przedział czasu do odjęcia |

### Wartość zwracana

Nowa instancja klasy [DateTime](../) reprezentująca wartość daty i czasu, która jest wynikiem odjęcia **duration** od wartości reprezentowanej przez bieżący obiekt.

## DateTime::Subtract(DateTime) const metoda


Zwraca instancję klasy [TimeSpan](../../timespan/) reprezentującą przedział czasu pomiędzy wartościami daty i czasu reprezentowanymi przez bieżący oraz określony obiekt.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [DateTime](../) | Instancja klasy [DateTime](../) oznaczająca jeden koniec obliczanego przedziału |

### Wartość zwracana

Instancja klasy [TimeSpan](../../timespan/) reprezentująca przedział czasu pomiędzy wartościami daty i czasu reprezentowanymi przez bieżący obiekt oraz **value**.

## Zobacz także

* Klasa [DateTime](../)
* Klasa [TimeSpan](../../timespan/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)
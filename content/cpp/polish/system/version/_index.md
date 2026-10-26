---
title: Version
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Reprezentuje numer wersji. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 1470
url: /pl/system/version/
---
## Klasa Version

Represents a version number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) klasy to manage objects of this type.

```cpp
class Version
```

## Metody

| Metoda | Opis |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Porównuje wersje reprezentowane przez bieżący obiekt oraz określony obiekt. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Określa, czy numery wersji reprezentowane przez bieżący i określony obiekt są równe. |
| int [get_Build](./get_build/)() const | Zwraca numer kompilacji. |
| int [get_Major](./get_major/)() const | Zwraca główną wersję. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Zwraca wysoką 16-bitową wartość numeru rewizji. |
| int [get_Minor](./get_minor/)() const | Zwraca wersję podrzędną. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Zwraca niską 16-bitową wartość numeru rewizji. |
| int [get_Revision](./get_revision/)() const | Zwraca numer rewizji. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu dla bieżącego obiektu. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Konwertuje tekstową reprezentację numeru wersji na równoważną instancję [Version](./) class. |
| [String](../string/) [ToString](./tostring/)() const | Zwraca tekstową reprezentację numeru wersji reprezentowanego przez bieżący obiekt. |
| [String](../string/) [ToString](./tostring/)(int) const | Zwraca tekstową reprezentację określonej liczby sekcji numeru wersji reprezentowanego przez bieżący obiekt. |
|  [Version](./version/)(int, int, int, int) | Tworzy instancję, która reprezentuje określone wartości głównej, podrzędnej, kompilacji i rewizji. |
|  [Version](./version/)(int, int, int) | Tworzy instancję, która reprezentuje określone wartości głównej, podrzędnej i kompilacji. |
|  [Version](./version/)(int, int) | Tworzy instancję, która reprezentuje określone wartości głównej i dodatkowej. |
|  [Version](./version/)(const [String](../string/)\&) | Tworzy instancję, która reprezentuje numer wersji podany jako ciąg znaków. |
|  [Version](./version/)() | Tworzy instancję, która reprezentuje numer wersji 0.0.-1.-1. |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)
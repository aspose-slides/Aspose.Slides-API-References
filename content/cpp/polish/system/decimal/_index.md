---
title: Decimal
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Reprezentuje liczbę dziesiętną. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 261
url: /pl/system/decimal/
---
## Decimal klasa


Reprezentuje liczbę dziesiętną. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

```cpp
class Decimal
```

## Metody

| Method | Description |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Dodaje dwie określone [Decimal](./) wartości. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Zwraca najmniejszą całkowitą wartość, która jest większa lub równa podanej wartości. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Określa, czy wartość reprezentowana przez pierwszy obiekt [Decimal](./) jest mniejsza, równa lub większa od wartości reprezentowanej przez drugi obiekt [Decimal](./). |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza, równa lub większa od wartości reprezentowanej przez określony obiekt. |
| [Decimal](./decimal/)() | Tworzy instancję, która reprezentuje 0. |
| [Decimal](./decimal/)(std::int8_t) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(std::int16_t) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(std::int32_t) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(std::int64_t) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(std::uint8_t) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(std::uint16_t) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(std::uint32_t) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(std::uint64_t) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(**float**) | Tworzy instancję, która reprezentuje podaną wartość. |
| [Decimal](./decimal/)(**double**) | Tworzy instancję, która reprezentuje podaną wartość. |
| explicit [Decimal](./decimal/)(const std::string\&) | Tworzy instancję, która reprezentuje wartość, której reprezentacja tekstowa jest podana jako instancja klasy std::string. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Tworzy obiekt [Decimal](./) z podanych składników. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Tworzy instancję klasy [Decimal](./), która reprezentuje tę samą liczbę co określony obiekt [Decimal](./). |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Tworzy instancję klasy [Decimal](./) z tablicy liczb całkowitych zawierającej reprezentację binarną. |
| [Decimal](./decimal/)(std::nullptr_t) | Zawsze rzuca wyjątek ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Tworzy instancję klasy [Decimal](./) reprezentującą podaną wartość. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Dzieli dwie określone wartości [Decimal](./). |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Określa, czy wartości reprezentowane przez bieżący obiekt i określony obiekt są równe. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Określa, czy wartości reprezentowane przez bieżący obiekt i określony obiekt są równe. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Określa, czy wartości reprezentowane przez podane obiekty są równe. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Zwraca największą wartość całkowitą, która jest mniejsza lub równa podanej wartości. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) podaną wartość waluty OLE na równoważną wartość [Decimal](./). NOT IMPLEMENTED. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Konwertuje podany obiekt [Decimal](./) na binarną reprezentację wartości, którą reprezentuje. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) podaną wartość [Decimal](./) na tablicę bajtów. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu dla bieżącego obiektu. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Pobiera kod typu obiektu. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Mnoży dwie określone wartości [Decimal](./). |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Zwraca nową instancję klasy [Decimal](./), która reprezentuje wartość będącą wynikiem negacji wartości reprezentowanej przez określony obiekt. |
| explicit [operator bool](./operator_bool/)() const | Konwertuje wartość reprezentowaną przez bieżący obiekt na wartość boolowską. |
| explicit [operator double](./operator_double/)() const | Konwertuje wartość reprezentowaną przez bieżący obiekt na liczbę zmiennoprzecinkową podwójnej precyzji. |
| explicit [operator float](./operator_float/)() const | Konwertuje wartość reprezentowaną przez bieżący obiekt na liczbę zmiennoprzecinkową pojedynczej precyzji. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Określa, czy wartości reprezentowane przez bieżący obiekt i określony obiekt nie są równe. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest różna od 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Zwraca nową instancję klasy [Decimal](./), która reprezentuje wartość będącą wynikiem operacji modulo na wartościach reprezentowanych przez bieżący i określony obiekt. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Przypisuje bieżącemu obiektowi nową wartość będącą wynikiem operacji modulo na wartościach reprezentowanych przez bieżący i określony obiekt. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Zwraca nową instancję klasy [Decimal](./), która reprezentuje wartość będącą wynikiem mnożenia wartości reprezentowanych przez bieżący i określony obiekt. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Przypisuje bieżącemu obiektowi nową wartość będącą wynikiem mnożenia wartości reprezentowanych przez bieżący i określony obiekt. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Zwraca nową instancję klasy [Decimal](./), która reprezentuje wartość będącą sumą wartości reprezentowanych przez bieżący i określony obiekt. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Zwiększa wartość reprezentowaną przez bieżący obiekt. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Przypisuje bieżącemu obiektowi nową wartość będącą sumą wartości reprezentowanych przez bieżący i określony obiekt. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Zwraca nową instancję klasy [Decimal](./), która reprezentuje wartość będącą wynikiem odjęcia wartości reprezentowanej przez określony obiekt od wartości reprezentowanej przez bieżący obiekt. |
| [Decimal](./) [operator-](./operator_minus/)() const | Zwraca nową instancję klasy [Decimal](./), która reprezentuje wartość będącą wynikiem negacji wartości reprezentowanej przez bieżący obiekt. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Zmniejsza wartość reprezentowaną przez bieżący obiekt. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Przypisuje bieżącemu obiektowi nową wartość będącą wynikiem odjęcia wartości reprezentowanej przez określony obiekt od wartości reprezentowanej przez bieżący obiekt. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Zwraca nową instancję klasy [Decimal](./), która reprezentuje wartość będącą wynikiem dzielenia wartości reprezentowanej przez bieżący obiekt przez wartość reprezentowaną przez określony obiekt. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Przypisuje bieżącemu obiektowi nową wartość będącą wynikiem dzielenia wartości reprezentowanej przez bieżący obiekt przez wartość reprezentowaną przez określony obiekt. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza od wartości reprezentowanej przez określony obiekt. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest mniejsza lub równa wartości reprezentowanej przez określony obiekt. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Przypisuje wartość reprezentowaną przez określony obiekt bieżącemu obiektowi. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Określa, czy wartości reprezentowane przez bieżący obiekt i określony obiekt są równe. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest równa 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest większa od wartości reprezentowanej przez określony obiekt. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Określa, czy wartość reprezentowana przez bieżący obiekt jest większa lub równa wartości reprezentowanej przez określony obiekt. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Konwertuje tekstową reprezentację liczby dziesiętnej na równoważną instancję klasy [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Konwertuje tekstową reprezentację liczby dziesiętnej na równoważną instancję klasy [Decimal](./) przy użyciu określonego stylu. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje tekstową reprezentację liczby dziesiętnej na równoważną instancję klasy [Decimal](./) przy użyciu określonego dostawcy formatów. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konwertuje tekstową reprezentację liczby dziesiętnej na równoważną instancję klasy [Decimal](./) przy użyciu określonego stylu i dostawcy formatów. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Oblicza resztę po podzieleniu dwóch wartości [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej liczby całkowitej. Parametr określa zachowanie funkcji, gdy podana wartość jest równo odległa od dwóch najbliższych liczb. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Zaokrągla podaną wartość do najbliższej wartości z określoną liczbą cyfr ułamkowych. Parametr określa zachowanie funkcji, gdy podana wartość jest równo odległa od dwóch najbliższych liczb. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Odejmuje jedną określoną wartość [Decimal](./) od drugiej. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na bez znaku 8-bitową wartość całkowitą. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na liczbę zmiennoprzecinkową podwójnej precyzji. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na 16-bitową wartość całkowitą ze znakiem. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na 32-bitową wartość całkowitą ze znakiem. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na 64-bitową wartość całkowitą ze znakiem. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) podaną wartość [Decimal](./) na równoważną wartość waluty OLE. NOT IMPLEMENTED. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na 8-bitową wartość całkowitą ze znakiem. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na 32-bitową liczbę zmiennoprzecinkową pojedynczej precyzji. |
| std::string [ToStdString](./tostdstring/)() const | Zwraca instancję std::string zawierającą tekstową reprezentację wartości reprezentowanej przez obiekt. |
| [String](../string/) [ToString](./tostring/)() const | Zwraca tekstową reprezentację wartości reprezentowanej przez obiekt. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konwertuje bieżący obiekt na łańcuch znaków przy użyciu informacji o formacie specyficznym dla kultury. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konwertuje bieżący obiekt na jego tekstową reprezentację przy użyciu określonego formatu łańcucha znaków i informacji o formacie specyficznych dla kultury dostarczonych przez określony obiekt [IFormatProvider](../iformatprovider/). |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Zwraca tekstową reprezentację wartości reprezentowanej przez obiekt. Do użytku wewnętrznego. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na 16-bitową wartość całkowitą bez znaku. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na 32-bitową wartość całkowitą bez znaku. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Konwertuje wartość [Decimal](./) na 64-bitową wartość całkowitą bez znaku. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Zwraca obiekt [Decimal](./) reprezentujący wartość, której część całkowita jest równa części całkowitej wartości reprezentowanej przez określony obiekt [Decimal](./), po odrzuceniu wszystkich cyfr ułamkowych. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Konwertuje podany łańcuch zawierający tekstową reprezentację liczby na równoważną wartość [Decimal](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Konwertuje podany łańcuch zawierający tekstową reprezentację liczby na równoważną wartość [Decimal](./) przy użyciu dostarczonych informacji o formacie i stylu liczby. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Zwraca odniesienie do obiektu [TypeInfo](../typeinfo/) reprezentującego informacje o typie klasy [Decimal](./). |
| [~Decimal](./~decimal/)() | Destruktor. |

## Pola

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | Reprezentuje największą liczbę, jaką może reprezentować klasa [Decimal](./). |
| static [MinusOne](./minusone/) | Reprezentuje liczbę -1. |
| static [MinValue](./minvalue/) | Reprezentuje najmniejszą liczbę, jaką może reprezentować klasa [Decimal](./). |
| static [One](./one/) | Reprezentuje liczbę 1. |
| static [Zero](./zero/) | Reprezentuje liczbę 0. |

## Typedefy

| Typedef | Description |
| --- | --- |
| [number_type](./number_type/) | Alias dla Detail::decimal_number_type. |

## Uwagi



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Ten przykład kodu generuje następujące wyjście:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)
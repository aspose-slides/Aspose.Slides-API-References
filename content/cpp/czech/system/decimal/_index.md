---
title: Decimal
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje desetinné číslo. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k správě objektů tohoto typu."
type: docs
weight: 261
url: /cs/system/decimal/
---
## Decimal třída

Reprezentuje desetinné číslo. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) k správě objektů tohoto typu.

```cpp
class Decimal
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Přidá dvě zadané hodnoty [Decimal](./). |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Vrátí nejmenší celočíselnou hodnotu, která je větší nebo rovna zadané hodnotě. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Určuje, zda hodnota reprezentovaná prvním objektem [Decimal](./) je menší, rovná se nebo větší než hodnota reprezentovaná druhým objektem [Decimal](./). |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Určuje, zda hodnota reprezentovaná aktuálním objektem je menší, rovná se nebo větší než hodnota reprezentovaná zadaným objektem. |
| [Decimal](./decimal/)() | Vytvoří instanci představující 0. |
| [Decimal](./decimal/)(std::int8_t) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(std::int16_t) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(std::int32_t) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(std::int64_t) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(std::uint8_t) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(std::uint16_t) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(std::uint32_t) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(std::uint64_t) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(**float**) | Vytvoří instanci představující zadanou hodnotu. |
| [Decimal](./decimal/)(**double**) | Vytvoří instanci představující zadanou hodnotu. |
| explicit [Decimal](./decimal/)(const std::string\&) | Vytvoří instanci představující hodnotu, jejíž řetězcová reprezentace je zadána jako instance třídy std::string. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Vytvoří objekt [Decimal](./) ze zadaných komponent. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Vytvoří instanci třídy [Decimal](./) představující stejné číslo jako zadaný objekt [Decimal](./). |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Vytvoří instanci třídy [Decimal](./) z pole celých čísel obsahujícího binární reprezentaci. |
| [Decimal](./decimal/)(std::nullptr_t) | Vždy vyhodí výjimku ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Vytvoří instanci třídy [Decimal](./) představující zadanou hodnotu. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Dělí dvě zadané hodnoty [Decimal](./). |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Určuje, zda jsou hodnoty reprezentované aktuálním a zadaným objektem rovny. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Určuje, zda jsou hodnoty reprezentované aktuálním a zadaným objektem rovny. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Určuje, zda jsou hodnoty reprezentované zadanými objekty rovny. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Vrátí největší celočíselnou hodnotu, která je menší nebo rovna zadané hodnotě. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) zadanou OLE měnovou hodnotu na ekvivalentní hodnotu [Decimal](./). NOT IMPLEMENTED. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Převádí zadaný objekt [Decimal](./) na binární reprezentaci hodnoty, kterou představuje. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) zadanou hodnotu [Decimal](./) na pole bytů. |
| int [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Získá kód typu objektu. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Násobí dvě zadané hodnoty [Decimal](./). |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Vrátí novou instanci třídy [Decimal](./) představující hodnotu, která vznikne negací hodnoty reprezentované zadaným objektem. |
| explicit [operator bool](./operator_bool/)() const | Převádí hodnotu reprezentovanou aktuálním objektem na logickou hodnotu. |
| explicit [operator double](./operator_double/)() const | Převádí hodnotu reprezentovanou aktuálním objektem na dvojitou přesnost. |
| explicit [operator float](./operator_float/)() const | Převádí hodnotu reprezentovanou aktuálním objektem na jednoduchou přesnost. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Určuje, zda jsou hodnoty reprezentované aktuálním a zadaným objektem nerovny. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem různá od 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Vrátí novou instanci třídy [Decimal](./) představující hodnotu, která je výsledkem modulo operace s hodnotami reprezentovanými aktuálním a zadaným objektem. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Přiřadí aktuálnímu objektu novou hodnotu, která je výsledkem modulo operace s hodnotami reprezentovanými aktuálním a zadaným objektem. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Vrátí novou instanci třídy [Decimal](./) představující hodnotu, která je výsledkem násobení hodnot reprezentovaných aktuálním a zadaným objektem. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Přiřadí aktuálnímu objektu novou hodnotu, která je výsledkem násobení hodnot reprezentovaných aktuálním a zadaným objektem. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Vrátí novou instanci třídy [Decimal](./) představující součet hodnot reprezentovaných aktuálním a zadaným objektem. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Zvýší hodnotu reprezentovanou aktuálním objektem. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Přiřadí aktuálnímu objektu novou hodnotu, která je součtem hodnot reprezentovaných aktuálním a zadaným objektem. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Vrátí novou instanci třídy [Decimal](./) představující hodnotu, která je výsledkem odečtení hodnoty reprezentované zadaným objektem od hodnoty reprezentované aktuálním objektem. |
| [Decimal](./) [operator-](./operator_minus/)() const | Vrátí novou instanci třídy [Decimal](./) představující hodnotu, která vznikne negací hodnoty reprezentované aktuálním objektem. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Sníží hodnotu reprezentovanou aktuálním objektem. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Přiřadí aktuálnímu objektu novou hodnotu, která je výsledkem odečtení hodnoty reprezentované zadaným objektem od hodnoty reprezentované aktuálním objektem. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Vrátí novou instanci třídy [Decimal](./) představující hodnotu, která je výsledkem dělení hodnoty reprezentované aktuálním objektem hodnotou reprezentovanou zadaným objektem. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Přiřadí aktuálnímu objektu novou hodnotu, která je výsledkem dělení hodnoty reprezentované aktuálním objektem hodnotou reprezentovanou zadaným objektem. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem menší než hodnota reprezentovaná zadaným objektem. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem menší nebo rovna hodnotě reprezentované zadaným objektem. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Přiřadí hodnotu reprezentovanou zadaným objektem aktuálnímu objektu. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Určuje, zda jsou hodnoty reprezentované aktuálním a zadaným objektem rovny. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem větší než hodnota reprezentovaná zadaným objektem. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Určuje, zda je hodnota reprezentovaná aktuálním objektem větší nebo rovna hodnotě reprezentované zadaným objektem. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Převádí řetězcovou reprezentaci desetinného čísla na ekvivalentní instanci třídy [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Převádí řetězcovou reprezentaci desetinného čísla na ekvivalentní instanci třídy [Decimal](./) s použitím zadaného stylu. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí řetězcovou reprezentaci desetinného čísla na ekvivalentní instanci třídy [Decimal](./) s použitím zadaného poskytovatele formátu. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Převádí řetězcovou reprezentaci desetinného čísla na ekvivalentní instanci třídy [Decimal](./) s použitím zadaného stylu a poskytovatele formátu. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Vypočítá zbytek po dělení dvou hodnot [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Zaokrouhluje zadanou hodnotu na nejbližší celé číslo. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Zaokrouhluje zadanou hodnotu na nejbližší hodnotu se zadaným počtem desetinných míst. Parametr určuje chování funkce, pokud je zadaná hodnota stejně blízko ke dvěma nejbližším číslům. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Odečte jednu zadanou hodnotu [Decimal](./) od druhé. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na nezápornou 8-bitovou celou hodnotu. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na číslo s dvojitou přesností. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na podepsanou 16-bitovou celou hodnotu. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na podepsanou 32-bitovou celou hodnotu. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na podepsanou 64-bitovou celou hodnotu. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) zadanou hodnotu [Decimal](./) na ekvivalentní OLE měnovou hodnotu. NOT IMPLEMENTED. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na podepsanou 8-bitovou celou hodnotu. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na číslo s jednoduchou přesností. |
| std::string [ToStdString](./tostdstring/)() const | Vrací instanci std::string obsahující řetězcovou reprezentaci hodnoty reprezentované objektem. |
| [String](../string/) [ToString](./tostring/)() const | Vrací řetězcovou reprezentaci hodnoty reprezentované objektem. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Převádí aktuální objekt na řetězec pomocí formátovacích informací specifických pro kulturu. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Převádí aktuální objekt na jeho řetězcovou reprezentaci pomocí zadaného řetězcového formátu a formátovacích informací specifických pro kulturu poskytnutých objektem [IFormatProvider](../iformatprovider/). |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Vrací řetězcovou reprezentaci hodnoty reprezentované objektem. Pro interní použití. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na nezápornou 16-bitovou celou hodnotu. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na nezápornou 32-bitovou celou hodnotu. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Převádí hodnotu [Decimal](./) na nezápornou 64-bitovou celou hodnotu. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Vrací objekt [Decimal](./) představující hodnotu, jejíž celočíselná část je rovna celočíselné části hodnoty reprezentované zadaným objektem [Decimal](./) s vynecháním všech desetinných míst. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu [Decimal](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Převádí zadaný řetězec obsahující řetězcovou reprezentaci čísla na ekvivalentní hodnotu [Decimal](./) pomocí poskytnutých formátovacích informací a číselného stylu. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Vrací referenci na objekt [TypeInfo](../typeinfo/) představující informace o typu třídy [Decimal](./). |
| [~Decimal](./~decimal/)() | Destruktor. |
## Pole

| Pole | Popis |
| --- | --- |
| static [MaxValue](./maxvalue/) | Reprezentuje největší číslo, které může být reprezentováno třídou [Decimal](./). |
| static [MinusOne](./minusone/) | Reprezentuje číslo -1. |
| static [MinValue](./minvalue/) | Reprezentuje nejmenší číslo, které může být reprezentováno třídou [Decimal](./). |
| static [One](./one/) | Reprezentuje číslo 1. |
| static [Zero](./zero/) | Reprezentuje číslo 0. |
## Typedefy

| Typedef | Popis |
| --- | --- |
| [number_type](./number_type/) | Alias pro Detail::decimal_number_type. |
## Poznámky



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
Tento příklad kódu produkuje následující výstup:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Viz také

* Namespace [System](../)
* Library [Aspose.Slides](../../)
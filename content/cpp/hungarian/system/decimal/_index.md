---
title: Decimal
second_title: Aspose.Slides C++ API referenciája
description: "Egy decimális számot reprezentál. Ezt a típust a stacken kell lefoglalni, és értékként vagy referenciaként kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 261
url: /hu/system/decimal/
---
## Decimal osztály

Egy decimális számot reprezentál. Ezt a típust a stacken kell lefoglalni, és értékként vagy referenciaként kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusú objektumok kezelésére.

```cpp
class Decimal
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Hozzáad két megadott [Decimal](./) értéket. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Visszaadja a legkisebb egész értéket, amely nagyobb vagy egyenlő a megadott értéknél. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Megállapítja, hogy az első [Decimal](./) objektum által reprezentált érték kisebb, egyenlő vagy nagyobb-e a második [Decimal](./) objektum által reprezentált értéknél. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Megállapítja, hogy a jelenlegi objektum által reprezentált érték kisebb, egyenlő vagy nagyobb-e a megadott objektum által reprezentált értéknél. |
| [Decimal](./decimal/)() | Létrehoz egy példányt, amely a 0-t reprezentálja. |
| [Decimal](./decimal/)(std::int8_t) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(std::int16_t) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(std::int32_t) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(std::int64_t) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(std::uint8_t) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(std::uint16_t) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(std::uint32_t) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(std::uint64_t) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(**float**) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| [Decimal](./decimal/)(**double**) | Létrehoz egy példányt, amely a megadott értéket reprezentálja. |
| explicit [Decimal](./decimal/)(const std::string\&) | Létrehoz egy példányt, amely egy olyan értéket reprezentál, amelynek karakterlánc ábrázolása std::string osztály egy példányaként van megadva. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Létrehoz egy [Decimal](./) objektumot a megadott komponensekből. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Létrehoz egy [Decimal](./) osztályú példányt, amely ugyanazt a számot reprezentálja, mint a megadott [Decimal](./) objektum. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Létrehoz egy [Decimal](./) osztályú példányt egy bináris ábrázolást tartalmazó egész szám tömbből. |
| [Decimal](./decimal/)(std::nullptr_t) | Mindig ArgumentNullException-t dob. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Létrehoz egy [Decimal](./) osztályú példányt, amely a megadott értéket reprezentálja. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Eloszt két megadott [Decimal](./) értéket. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Megállapítja, hogy a jelenlegi objektum és a megadott objektum által reprezentált értékek egyenlőek-e. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Megállapítja, hogy a jelenlegi objektum és a megadott objektum által reprezentált értékek egyenlőek-e. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Megállapítja, hogy a megadott objektumok által reprezentált értékek egyenlőek-e. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Visszaadja a legnagyobb egész értéket, amely kisebb vagy egyenlő a megadott értéknél. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) a megadott OLE pénznem értéket az ekvivalens [Decimal](./) értékre. NEM VALÓSÍTOTT. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Átalakítja a megadott [Decimal](./) objektumot a reprezentált érték bináris ábrázolásává. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) a megadott [Decimal](./) értéket egy bájt tömbbé. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumhoz. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Lekéri az objektum típuskódját. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Összeszoroz két megadott [Decimal](./) értéket. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Visszaad egy új [Decimal](./) osztályú példányt, amely egy értéket reprezentál, amely a megadott objektum által reprezentált érték negatívja. |
| explicit [operator bool](./operator_bool/)() const | Átalakítja a jelenlegi objektum által reprezentált értéket logikai értékké. |
| explicit [operator double](./operator_double/)() const | Átalakítja a jelenlegi objektum által reprezentált értéket dupla pontosságú lebegőpontos számmá. |
| explicit [operator float](./operator_float/)() const | Átalakítja a jelenlegi objektum által reprezentált értéket egyszeres pontosságú lebegőpontos számmá. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Megállapítja, hogy a jelenlegi objektum és a megadott objektum által reprezentált értékek nem egyenlőek-e. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Megállapítja, hogy a jelenlegi objektum által reprezentált érték különbözik-e a 0-tól. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Visszaad egy új [Decimal](./) osztályú példányt, amely a jelenlegi és a megadott objektumok által reprezentált értékek modulo műveletének eredményét reprezentálja. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | A jelenlegi objektumnak egy új értéket ad, amely a jelenlegi és a megadott objektumok által reprezentált értékek modulo műveletének eredménye. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Visszaad egy új [Decimal](./) osztályú példányt, amely a jelenlegi és a megadott objektumok által reprezentált értékek szorzásának eredményét reprezentálja. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | A jelenlegi objektumnak egy új értéket ad, amely a jelenlegi és a megadott objektumok által reprezentált értékek szorzásának eredménye. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Visszaad egy új [Decimal](./) osztályú példányt, amely a jelenlegi és a megadott objektumok által reprezentált értékek összegét reprezentálja. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Növeli a jelenlegi objektum által reprezentált értéket. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | A jelenlegi objektumnak egy új értéket ad, amely a jelenlegi és a megadott objektumok által reprezentált értékek összegét adja. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Visszaad egy új [Decimal](./) osztályú példányt, amely a jelenlegi objektum által reprezentált értékből a megadott objektum által reprezentált érték kivonásának eredményét reprezentálja. |
| [Decimal](./) [operator-](./operator_minus/)() const | Visszaad egy új [Decimal](./) osztályú példányt, amely a jelenlegi objektum által reprezentált érték negatívjának eredményét reprezentálja. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Csökkenti a jelenlegi objektum által reprezentált értéket. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | A jelenlegi objektumnak egy új értéket ad, amely a megadott objektum által reprezentált érték levonásának eredménye a jelenlegi objektum értékéből. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Visszaad egy új [Decimal](./) osztályú példányt, amely a jelenlegi objektum által reprezentált érték és a megadott objektum által reprezentált érték osztásának eredményét reprezentálja. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | A jelenlegi objektumnak egy új értéket ad, amely a jelenlegi objektum által reprezentált érték és a megadott objektum által reprezentált érték osztásának eredménye. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Megállapítja, hogy a jelenlegi objektum által reprezentált érték kisebb-e a megadott objektum által reprezentált értéknél. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Megállapítja, hogy a jelenlegi objektum által reprezentált érték kisebb vagy egyenlő-e a megadott objektum által reprezentált értéknél. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | A megadott objektum által reprezentált értéket a jelenlegi objektumra rendeli. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Megállapítja, hogy a jelenlegi objektum és a megadott objektum által reprezentált értékek egyenlőek-e. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Megállapítja, hogy a jelenlegi objektum által reprezentált érték 0-e. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Megállapítja, hogy a jelenlegi objektum által reprezentált érték nagyobb-e a megadott objektum által reprezentált értéknél. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Megállapítja, hogy a jelenlegi objektum által reprezentált érték nagyobb vagy egyenlő-e a megadott objektum által reprezentált értéknél. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a decimális szám karakterlánc ábrázolását az ekvivalens [Decimal](./) osztályú példánnyá. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Átalakítja a decimális szám karakterlánc ábrázolását az ekvivalens [Decimal](./) osztályú példánnyá a megadott stílus használatával. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a decimális szám karakterlánc ábrázolását az ekvivalens [Decimal](./) osztályú példánnyá a megadott formátum-szolgáltató használatával. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Átalakítja a decimális szám karakterlánc ábrázolását az ekvivalens [Decimal](./) osztályú példánnyá a megadott stílus és formátum-szolgáltató használatával. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Kiszámítja a maradékot két [Decimal](./) érték osztása után. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a legközelebbi egész számra. Egy paraméter meghatározza a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Kerekíti a megadott értéket a legközelebbi értékre a megadott számú tizedesjeggyel. Egy paraméter meghatározza a függvény viselkedését, ha a megadott érték egyformán közel van a két legközelebbi számhoz. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Kivon egy megadott [Decimal](./) értéket egy másikból. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket 8 bites előjel nélküli egész számmá. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket dupla pontosságú lebegőpontos számmá. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket 16 bites előjeles egész számmá. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket 32 bites előjeles egész számmá. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket 64 bites előjeles egész számmá. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) a megadott [Decimal](./) értéket az ekvivalens OLE pénznem értékre. NEM VALÓSÍTOTT. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket 8 bites előjeles egész számmá. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket egyszeres pontosságú lebegőpontos számmá. |
| std::string [ToStdString](./tostdstring/)() const | Visszaad egy std::string példányt, amely az objektum által reprezentált érték karakterlánc ábrázolását tartalmazza. |
| [String](../string/) [ToString](./tostring/)() const | Visszaadja az objektum által reprezentált érték karakterlánc ábrázolását. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Átalakítja a jelenlegi objektumot karakterláncba a kultúraspecifikus formázási információk használatával. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Átalakítja a jelenlegi objektumot a saját karakterlánc ábrázolásává a megadott karakterlánc formátum és a megadott [IFormatProvider](../iformatprovider/) objektum által biztosított kultúraspecifikus formázási információk használatával. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Visszaadja az objektum által reprezentált érték karakterlánc ábrázolását. Belső használatra. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket 16 bites előjel nélküli egész számmá. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket 32 bites előjel nélküli egész számmá. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Átalakítja a [Decimal](./) értéket 64 bites előjel nélküli egész számmá. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Visszaadja a [Decimal](./) objektumot, amely egy olyan értéket reprezentál, amelynek egész része megegyezik a megadott [Decimal](./) objektum által reprezentált érték egész részével, minden tört rész eltávolítva. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Átalakítja a megadott, egy szám karakterlánc ábrázolását tartalmazó sztringet az ekvivalens [Decimal](./) értékké. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Átalakítja a megadott, egy szám karakterlánc ábrázolását tartalmazó sztringet a megadott formázási információk és szám stílus segítségével az ekvivalens [Decimal](./) értékké. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Visszaad egy referenciát a [TypeInfo](../typeinfo/) objektumra, amely a [Decimal](./) osztály típusinformációját reprezentálja. |
| [~Decimal](./~decimal/)() | Megsemmisítő. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [MaxValue](./maxvalue/) | Representálja a legnagyobb számot, amelyet a [Decimal](./) osztály képes reprezentálni. |
| static [MinusOne](./minusone/) | Representálja a -1 számot. |
| static [MinValue](./minvalue/) | Representálja a legkisebb számot, amelyet a [Decimal](./) osztály képes reprezentálni. |
| static [One](./one/) | Representálja az 1 számot. |
| static [Zero](./zero/) | Representálja a 0 számot. |

## Typedefek

| Typedef | Leírás |
| --- | --- |
| [number_type](./number_type/) | A Detail::decimal_number_type alias-a. |

## Megjegyzések

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
Ez a kódrészlet a következő kimenetet eredményezi:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)
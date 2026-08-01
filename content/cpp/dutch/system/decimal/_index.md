---
title: Decimal
second_title: Aspose.Slides voor C++ API-referentie
description: "Representeert een decimaal getal. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 261
url: /nl/system/decimal/
---
## Decimale klasse

Stelt een decimaal getal voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Decimal
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Voegt twee opgegeven [Decimal](./) waarden toe. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Retourneert de kleinste gehele waarde die groter dan of gelijk aan de opgegeven waarde is. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Bepaalt of de waarde die wordt weergegeven door het eerste [Decimal](./) object kleiner is dan, gelijk is aan of groter is dan de waarde die wordt weergegeven door het tweede [Decimal](./) object. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Bepaalt of de waarde die wordt weergegeven door het huidige object kleiner is dan, gelijk is aan of groter is dan de waarde die wordt weergegeven door het opgegeven object. |
| [Decimal](./decimal/)() | Construeert een instantie die 0 vertegenwoordigt. |
| [Decimal](./decimal/)(std::int8_t) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(std::int16_t) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(std::int32_t) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(std::int64_t) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(std::uint8_t) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(std::uint16_t) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(std::uint32_t) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(std::uint64_t) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(**float**) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| [Decimal](./decimal/)(**double**) | Construeert een instantie die de opgegeven waarde vertegenwoordigt. |
| explicit [Decimal](./decimal/)(const std::string\&) | Construeert een instantie die een waarde vertegenwoordigt waarvan de tekenreeksrepresentatie is opgegeven als een instantie van de std::string klasse. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Construeert een [Decimal](./) object uit de opgegeven componenten. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Construeert een instantie van de [Decimal](./) klasse die hetzelfde getal vertegenwoordigt als het opgegeven [Decimal](./) object. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Construeert een instantie van de [Decimal](./) klasse uit een geheel getallenarray die een binaire representatie bevat. |
| [Decimal](./decimal/)(std::nullptr_t) | Gooit altijd een ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Construeert een instantie van de [Decimal](./) klasse die de opgegeven waarde vertegenwoordigt. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Deelt twee opgegeven [Decimal](./) waarden. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Bepaalt of de waarden die worden weergegeven door het huidige object en het opgegeven object gelijk zijn. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Bepaalt of de waarden die worden weergegeven door het huidige object en het opgegeven object gelijk zijn. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Bepaalt of de waarden die door de opgegeven objecten worden weergegeven gelijk zijn. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Retourneert de grootste gehele waarde die kleiner dan of gelijk aan de opgegeven waarde is. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) de opgegeven OLE-valutawaarde naar de equivalente [Decimal](./) waarde. NIET GEÏMPLENTEERD. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Converteert het opgegeven [Decimal](./) object naar de binaire representatie van de waarde die het vertegenwoordigt. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) de opgegeven [Decimal](./) waarde naar een byte-array. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Haalt de objecttypecode op. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Vermenigvuldigt twee opgegeven [Decimal](./) waarden. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Retourneert een nieuwe instantie van de [Decimal](./) klasse die een waarde vertegenwoordigt die het resultaat is van de negatie van de door het opgegeven object vertegenwoordigde waarde. |
| explicit [operator bool](./operator_bool/)() const | Converteert de waarde die door het huidige object wordt weergegeven naar een booleaanse waarde. |
| explicit [operator double](./operator_double/)() const | Converteert de waarde die door het huidige object wordt weergegeven naar een double-precisie floating-point waarde. |
| explicit [operator float](./operator_float/)() const | Converteert de waarde die door het huidige object wordt weergegeven naar een single-precisie floating-point waarde. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Bepaalt of de waarden die worden weergegeven door het huidige object en het opgegeven object niet gelijk zijn. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Bepaalt of de door het huidige object weergegeven waarde verschillend is van 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Retourneert een nieuwe instantie van de [Decimal](./) klasse die een waarde vertegenwoordigt die het resultaat is van een modulo-bewerking met de waarden die door het huidige en het opgegeven object worden weergegeven. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Kent aan het huidige object een nieuwe waarde toe die het resultaat is van een modulo-bewerking met de waarden die door het huidige en het opgegeven object worden weergegeven. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Retourneert een nieuwe instantie van de [Decimal](./) klasse die een waarde vertegenwoordigt die het resultaat is van de multiplicatie van de door het huidige en de opgegeven objecten weergegeven waarden. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Kent aan het huidige object een nieuwe waarde toe die het resultaat is van de multiplicatie van de door het huidige en de opgegeven objecten weergegeven waarden. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Retourneert een nieuwe instantie van de [Decimal](./) klasse die een waarde vertegenwoordigt die de som is van de door het huidige en het opgegeven objecten weergegeven waarden. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Verhoogt de door het huidige object weergegeven waarde. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Kent aan het huidige object een nieuwe waarde toe die de som is van de door het huidige en het opgegeven objecten weergegeven waarden. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Retourneert een nieuwe instantie van de [Decimal](./) klasse die een waarde vertegenwoordigt die het resultaat is van het aftrekken van de door het opgegeven object weergegeven waarde van de door het huidige object weergegeven waarde. |
| [Decimal](./) [operator-](./operator_minus/)() const | Retourneert een nieuwe instantie van de [Decimal](./) klasse die een waarde vertegenwoordigt die het resultaat is van de negatie van de door het huidige object weergegeven waarde. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Verlaagt de door het huidige object weergegeven waarde. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Kent aan het huidige object een nieuwe waarde toe die het resultaat is van het aftrekken van de door het opgegeven object weergegeven waarde van de door het huidige object weergegeven waarde. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Retourneert een nieuwe instantie van de [Decimal](./) klasse die een waarde vertegenwoordigt die het resultaat is van de deling van de door het huidige object weergegeven waarde door de door het opgegeven object weergegeven waarde. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Kent aan het huidige object een nieuwe waarde toe die het resultaat is van de deling van de door het huidige object weergegeven waarde door de door het opgegeven object weergegeven waarde. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Bepaalt of de door het huidige object weergegeven waarde kleiner is dan de door het opgegeven object weergegeven waarde. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Bepaalt of de door het huidige object weergegeven waarde kleiner dan of gelijk aan de door het opgegeven object weergegeven waarde is. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Kent de door het opgegeven object weergegeven waarde toe aan het huidige object. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Bepaalt of de waarden die door het huidige object en het opgegeven object worden weergegeven gelijk zijn. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Bepaalt of de door het huidige object weergegeven waarde 0 is. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Bepaalt of de door het huidige object weergegeven waarde groter is dan de door het opgegeven object weergegeven waarde. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Bepaalt of de door het huidige object weergegeven waarde groter dan of gelijk aan de door het opgegeven object weergegeven waarde is. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Converteert de tekenreeksrepresentatie van een decimale getal naar een equivalente instantie van de [Decimal](./) klasse. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Converteert de tekenreeksrepresentatie van een decimale getal naar een equivalente instantie van de [Decimal](./) klasse met behulp van de opgegeven stijl. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de tekenreeksrepresentatie van een decimale getal naar een equivalente instantie van de [Decimal](./) klasse met behulp van de opgegeven formatprovider. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Converteert de tekenreeksrepresentatie van een decimale getal naar een equivalente instantie van de [Decimal](./) klasse met behulp van de opgegeven stijl en formatprovider. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Berekent de rest na het delen van twee [Decimal](./) waarden. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Rondt de opgegeven waarde af naar het dichtstbijzijnde gehele getal. Een parameter bepaalt het gedrag van de functie als de opgegeven waarde even dicht bij twee dichtstbijzijnde getallen ligt. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Rondt de opgegeven waarde af naar de dichtstbijzijnde waarde met het opgegeven aantal fractionele cijfers. Een parameter bepaalt het gedrag van de functie als de opgegeven waarde even dicht bij twee dichtstbijzijnde waarden ligt. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Trek één opgegeven [Decimal](./) waarde af van een andere. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een unsigned 8-bit integer waarde. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een double-precisie floating-point getal. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een signed 16-bit integer waarde. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een signed 32-bit integer waarde. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een signed 64-bit integer waarde. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) de opgegeven [Decimal](./) waarde naar de equivalente OLE-valutawaarde. NIET GEÏMPLENTEERD. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een signed 8-bit integer waarde. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een single-precisie floating-point getal. |
| std::string [ToStdString](./tostdstring/)() const | Retourneert een instantie van std::string die de tekenreeksrepresentatie van de door het object weergegeven waarde bevat. |
| [String](../string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van de door het object weergegeven waarde. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converteert het huidige object naar een string met behulp van cultuurspecifieke opmaakinformatie. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converteert het huidige object naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en cultuurspecifieke opmaakinformatie geleverd door het opgegeven [IFormatProvider](../iformatprovider/) object. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Retourneert de tekenreeksrepresentatie van de door het object weergegeven waarde. Voor intern gebruik. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een unsigned 16-bit integer waarde. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een unsigned 32-bit integer waarde. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Converteert de [Decimal](./) waarde naar een unsigned 64-bit integer waarde. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Retourneert het [Decimal](./) object dat een waarde vertegenwoordigt waarvan het gehele gedeelte gelijk is aan dat van de door het opgegeven [Decimal](./) object weergegeven waarde, waarbij alle fractionele cijfers worden verwijderd. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente [Decimal](./) waarde. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente [Decimal](./) waarde met behulp van de verstrekte opmaakinformatie en getalstijl. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retourneert een referentie naar het [TypeInfo](../typeinfo/) object dat de type-informatie van de [Decimal](./) klasse vertegenwoordigt. |
| [~Decimal](./~decimal/)() | Destructor. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [MaxValue](./maxvalue/) | Stelt het grootste getal voor dat kan worden vertegenwoordigd door de [Decimal](./) klasse. |
| static [MinusOne](./minusone/) | Stelt het getal -1 voor. |
| static [MinValue](./minvalue/) | Stelt het kleinste getal voor dat kan worden vertegenwoordigd door de [Decimal](./) klasse. |
| static [One](./one/) | Stelt het getal 1 voor. |
| static [Zero](./zero/) | Stelt het getal 0 voor. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [number_type](./number_type/) | Een alias voor Detail::decimal_number_type. |

## Opmerkingen



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
Dit codevoorbeeld produceert de volgende output:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Zie ook

* Namespace [System](../)
* Library [Aspose.Slides](../../)
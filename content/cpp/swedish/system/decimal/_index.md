---
title: Decimal
second_title: Aspose.Slides för C++ API-referens
description: "Representerar ett decimaltal. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller som referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ."
type: docs
weight: 261
url: /sv/system/decimal/
---
## Decimal klass

Representerar ett decimaltal. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../smartptr/)-klassen för att hantera objekt av denna typ.

```cpp
class Decimal
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Adderar två angivna [Decimal](./)-värden. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Returnerar det minsta heltalsvärdet som är större än eller lika med det angivna värdet. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Bestämmer om värdet som representeras av det första [Decimal](./)-objektet är mindre än, lika med eller större än värdet som representeras av det andra [Decimal](./)-objektet. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än, lika med eller större än värdet som representeras av det angivna objektet. |
| [Decimal](./decimal/)() | Skapar en instans som representerar 0. |
| [Decimal](./decimal/)(std::int8_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::int16_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::int32_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::int64_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::uint8_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::uint16_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::uint32_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(std::uint64_t) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(**float**) | Skapar en instans som representerar det angivna värdet. |
| [Decimal](./decimal/)(**double**) | Skapar en instans som representerar det angivna värdet. |
| explicit [Decimal](./decimal/)(const std::string\&) | Skapar en instans som representerar ett värde vars strängrepresentation specificeras som en instans av std::string-klassen. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Skapar ett [Decimal](./)-objekt från de angivna komponenterna. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Skapar en instans av [Decimal](./)-klassen som representerar samma tal som det angivna [Decimal](./)-objektet. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Skapar en instans av [Decimal](./)-klassen från en heltalsarray som innehåller en binär representation. |
| [Decimal](./decimal/)(std::nullptr_t) | Kastar alltid ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Skapar en instans av [Decimal](./)-klassen som representerar det angivna värdet. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Dividerar två angivna [Decimal](./)-värden. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Bestämmer om värdena som representeras av det aktuella objektet och det angivna objektet är lika. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Bestämmer om värdena som representeras av det aktuella objektet och det angivna objektet är lika. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Bestämmer om värdena som representeras av de angivna objekten är lika. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Returnerar det största heltalsvärdet som är mindre än eller lika med det angivna värdet. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) det angivna OLE-valutavärdet till motsvarande [Decimal](./)-värde. NOT IMPLEMENTED. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Konverterar det angivna [Decimal](./)-objektet till den binära representationen av det värde det representerar. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) det angivna [Decimal](./)-värdet till en bytearray. |
| int [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Hämtar objektets typkod. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Multiplicerar två angivna [Decimal](./)-värden. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Returnerar en ny instans av [Decimal](./)-klassen som representerar ett värde som erhålls genom negation av värdet som representeras av det angivna objektet. |
| explicit [operator bool](./operator_bool/)() const | Konverterar värdet som representeras av det aktuella objektet till ett booleskt värde. |
| explicit [operator double](./operator_double/)() const | Konverterar värdet som representeras av det aktuella objektet till ett dubbelprecisions-flytande tal. |
| explicit [operator float](./operator_float/)() const | Konverterar värdet som representeras av det aktuella objektet till ett enkelprecisions-flytande tal. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Bestämmer om värdena som representeras av det aktuella objektet och det angivna objektet inte är lika. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Bestämmer om värdet som representeras av det aktuella objektet är annorlunda än 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Returnerar en ny instans av [Decimal](./)-klassen som representerar ett värde som är resultatet av en modulär operation med värdena som representeras av det aktuella och det angivna objektet. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Tilldelar det aktuella objektet ett nytt värde som är resultatet av en modulär operation med värdena som representeras av det aktuella och det angivna objektet. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Returnerar en ny instans av [Decimal](./)-klassen som representerar ett värde som är resultatet av multiplikation av värdena som representeras av det aktuella och det specificerade objektet. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Tilldelar det aktuella objektet ett nytt värde som är resultatet av multiplikation av värdena som representeras av det aktuella och det specificerade objektet. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Returnerar en ny instans av [Decimal](./)-klassen som representerar ett värde som är summan av värdena som representeras av det aktuella och det specificerade objektet. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Ökar värdet som representeras av det aktuella objektet. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Tilldelar det aktuella objektet ett nytt värde som är summan av värdena som representeras av det aktuella och det specificerade objektet. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Returnerar en ny instans av [Decimal](./)-klassen som representerar ett värde som är resultatet av subtraktion av värdet som representeras av det angivna objektet från värdet som representeras av det aktuella objektet. |
| [Decimal](./) [operator-](./operator_minus/)() const | Returnerar en ny instans av [Decimal](./)-klassen som representerar ett värde som erhålls genom negation av värdet som representeras av det aktuella objektet. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Minskar värdet som representeras av det aktuella objektet. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Tilldelar det aktuella objektet ett nytt värde som är resultatet av subtraktion av värdet som representeras av det angivna objektet från värdet som representeras av det aktuella objektet. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Returnerar en ny instans av [Decimal](./)-klassen som representerar ett värde som är resultatet av division av värdet som representeras av det aktuella objektet med värdet som representeras av det angivna objektet. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Tilldelar det aktuella objektet ett nytt värde som är resultatet av division av värdet som representeras av det aktuella objektet med värdet som representeras av det angivna objektet. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än värdet som representeras av det angivna objektet. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Bestämmer om värdet som representeras av det aktuella objektet är mindre än eller lika med värdet som representeras av det angivna objektet. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Tilldelar värdet som representeras av det angivna objektet till det aktuella objektet. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Bestämmer om värdena som representeras av det aktuella objektet och det angivna objektet är lika. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Bestämmer om värdet som representeras av det aktuella objektet är 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än värdet som representeras av det angivna objektet. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Bestämmer om värdet som representeras av det aktuella objektet är större än eller lika med värdet som representeras av det angivna objektet. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av [Decimal](./)-klassen. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av [Decimal](./)-klassen med den angivna stilen. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av [Decimal](./)-klassen med den angivna formatleverantören. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konverterar strängrepresentationen av ett decimaltal till en motsvarande instans av [Decimal](./)-klassen med den angivna stilen och formatleverantören. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Beräknar resten efter division av två [Decimal](./)-värden. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste heltal. En parameter specificerar funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Avrundar det angivna värdet till närmaste värde med det angivna antalet decimaler. En parameter specificerar funktionens beteende om det angivna värdet är lika nära två närmaste tal. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Subtraherar ett angivet [Decimal](./)-värde från ett annat. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett osignerat 8-bit heltal. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett dubbelprecisions-flytande tal. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett signerat 16-bit heltal. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett signerat 32-bit heltal. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett signerat 64-bit heltal. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) det angivna [Decimal](./)-värdet till motsvarande OLE-valutavärde. NOT IMPLEMENTED. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett signerat 8-bit heltal. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett enkelprecisions-flytande tal. |
| std::string [ToStdString](./tostdstring/)() const | Returnerar en instans av std::string som innehåller strängrepresentationen av värdet som representeras av objektet. |
| [String](../string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av värdet som representeras av objektet. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konverterar aktuellt objekt till sträng med kultur-specifik formatinformation. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konverterar aktuellt objekt till dess strängrepresentation med angivet strängformat och kultur-specifik formatinformation från det angivna [IFormatProvider](../iformatprovider/)-objektet. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Returnerar strängrepresentationen av värdet som representeras av objektet. For internal use. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett osignerat 16-bit heltal. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett osignerat 32-bit heltal. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Konverterar [Decimal](./)-värdet till ett osignerat 64-bit heltal. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Returnerar [Decimal](./)-objektet som representerar ett värde vars heltalsdel är lika med den för det angivna [Decimal](./)-objektet, med alla decimaler bortkastade. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Konverterar den angivna strängen som innehåller en siffra till motsvarande [Decimal](./)-värde. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Konverterar den angivna strängen som innehåller en siffra till motsvarande [Decimal](./)-värde med angiven formateringsinformation och talstil. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Returnerar en referens till [TypeInfo](../typeinfo/)-objektet som representerar [Decimal](./)-klassens typinformation. |
| [~Decimal](./~decimal/)() | Destruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [MaxValue](./maxvalue/) | Representerar det största tal som kan representeras av [Decimal](./)-klassen. |
| static [MinusOne](./minusone/) | Representerar talet -1. |
| static [MinValue](./minvalue/) | Representerar det minsta tal som kan representeras av [Decimal](./)-klassen. |
| static [One](./one/) | Representerar talet 1. |
| static [Zero](./zero/) | Representerar talet 0. |
## Typdefinitioner

| Typdefinition | Beskrivning |
| --- | --- |
| [number_type](./number_type/) | Ett alias för Detail::decimal_number_type. |
## Anmärkningar



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
Det här kodexemplet producerar följande utdata:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
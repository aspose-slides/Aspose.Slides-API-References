---
title: Decimal
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt eine dezimale Zahl dar. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 261
url: /de/system/decimal/
---
## Decimal Klasse

Stellt eine dezimale Zahl dar. Dieser Typ sollte auf dem Stapel alloziert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class Decimal
```

## Methoden

| Method | Description |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Addiert zwei angegebene [Decimal](./) Werte. |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Gibt den kleinsten ganzzahligen Wert zurück, der größer als oder gleich dem angegebenen Wert ist. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Bestimmt, ob der vom ersten [Decimal](./) Objekt dargestellte Wert kleiner, gleich oder größer ist als der vom zweiten [Decimal](./) Objekt dargestellte Wert. |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner, gleich oder größer ist als der vom angegebenen Objekt dargestellte Wert. |
| [Decimal](./decimal/)() | Konstruiert eine Instanz, die 0 darstellt. |
| [Decimal](./decimal/)(std::int8_t) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(std::int16_t) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(std::int32_t) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(std::int64_t) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(std::uint8_t) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(std::uint16_t) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(std::uint32_t) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(std::uint64_t) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(**float**) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| [Decimal](./decimal/)(**double**) | Konstruiert eine Instanz, die den angegebenen Wert darstellt. |
| explicit  [Decimal](./decimal/)(const std::string\&) | Konstruiert eine Instanz, die einen Wert darstellt, dessen Zeichenkettenrepräsentation als Instanz der std::string Klasse angegeben ist. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Konstruiert ein [Decimal](./) Objekt aus den angegebenen Komponenten. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Konstruiert eine Instanz der [Decimal](./) Klasse, die dieselbe Zahl wie das angegebene [Decimal](./) Objekt darstellt. |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Konstruiert eine Instanz der [Decimal](./) Klasse aus einem Integer-Array, das eine Binärdarstellung enthält. |
| [Decimal](./decimal/)(std::nullptr_t) | Wirft immer ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Konstruiert eine Instanz der [Decimal](./) Klasse, die den angegebenen Wert darstellt. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Dividiert zwei angegebene [Decimal](./) Werte. |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Bestimmt, ob die vom aktuellen Objekt und dem angegebenen Objekt dargestellten Werte gleich sind. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Bestimmt, ob die vom aktuellen Objekt und dem angegebenen Objekt dargestellten Werte gleich sind. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Bestimmt, ob die von den angegebenen Objekten dargestellten Werte gleich sind. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Gibt den größten ganzzahligen Wert zurück, der kleiner als oder gleich dem angegebenen Wert ist. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) den angegebenen OLE-Währungswert zum entsprechenden [Decimal](./) Wert. NICHT IMPLEMENTIERT. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Konvertiert das angegebene [Decimal](./) Objekt in die Binärdarstellung des von ihm dargestellten Wertes. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) den angegebenen [Decimal](./) Wert in ein Byte-Array. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Ermittelt den Objekttypcode. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Multipliziert zwei angegebene [Decimal](./) Werte. |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Gibt eine neue Instanz der [Decimal](./) Klasse zurück, die einen Wert darstellt, der durch Negation des vom angegebenen Objekt dargestellten Wertes entsteht. |
| explicit  [operator bool](./operator_bool/)() const | Konvertiert den vom aktuellen Objekt dargestellten Wert in einen booleschen Wert. |
| explicit  [operator double](./operator_double/)() const | Konvertiert den vom aktuellen Objekt dargestellten Wert in einen double-Genauigkeitsfließkommawert. |
| explicit  [operator float](./operator_float/)() const | Konvertiert den vom aktuellen Objekt dargestellten Wert in einen single-Genauigkeitsfließkommawert. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Bestimmt, ob die vom aktuellen Objekt und dem angegebenen Objekt dargestellten Werte ungleich sind. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert von 0 verschieden ist. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Gibt eine neue Instanz der [Decimal](./) Klasse zurück, die einen Wert darstellt, der das Ergebnis der Modulo-Operation mit den vom aktuellen und dem angegebenen Objekt dargestellten Werten ist. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Weist dem aktuellen Objekt einen neuen Wert zu, der das Ergebnis der Modulo-Operation mit den vom aktuellen und dem angegebenen Objekt dargestellten Werten ist. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Gibt eine neue Instanz der [Decimal](./) Klasse zurück, die einen Wert darstellt, der das Ergebnis der Multiplikation der vom aktuellen und dem angegebenen Objekt dargestellten Werte ist. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Weist dem aktuellen Objekt einen neuen Wert zu, der das Ergebnis der Multiplikation der vom aktuellen und dem angegebenen Objekt dargestellten Werte ist. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Gibt eine neue Instanz der [Decimal](./) Klasse zurück, die einen Wert darstellt, der die Summe der vom aktuellen und dem angegebenen Objekt dargestellten Werte ist. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Erhöht den vom aktuellen Objekt dargestellten Wert. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Weist dem aktuellen Objekt einen neuen Wert zu, der die Summe der vom aktuellen und dem angegebenen Objekt dargestellten Werte ist. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Gibt eine neue Instanz der [Decimal](./) Klasse zurück, die einen Wert darstellt, der das Ergebnis der Subtraktion des vom angegebenen Objekt dargestellten Wertes vom vom aktuellen Objekt dargestellten Wert ist. |
| [Decimal](./) [operator-](./operator_minus/)() const | Gibt eine neue Instanz der [Decimal](./) Klasse zurück, die einen Wert darstellt, der durch Negation des vom aktuellen Objekt dargestellten Wertes entsteht. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Verringert den vom aktuellen Objekt dargestellten Wert. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Weist dem aktuellen Objekt einen neuen Wert zu, der das Ergebnis der Subtraktion des vom angegebenen Objekt dargestellten Wertes vom vom aktuellen Objekt dargestellten Wert ist. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Gibt eine neue Instanz der [Decimal](./) Klasse zurück, die einen Wert darstellt, der das Ergebnis der Division des vom aktuellen Objekt dargestellten Wertes durch den vom angegebenen Objekt dargestellten Wert ist. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Weist dem aktuellen Objekt einen neuen Wert zu, der das Ergebnis der Division des vom aktuellen Objekt dargestellten Wertes durch den vom angegebenen Objekt dargestellten Wert ist. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner ist als der vom angegebenen Objekt dargestellte Wert. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert kleiner oder gleich dem vom angegebenen Objekt dargestellten Wert ist. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Weist dem aktuellen Objekt den vom angegebenen Objekt dargestellten Wert zu. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Bestimmt, ob die vom aktuellen Objekt und dem angegebenen Objekt dargestellten Werte gleich sind. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert 0 ist. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer ist als der vom angegebenen Objekt dargestellte Wert. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Bestimmt, ob der vom aktuellen Objekt dargestellte Wert größer oder gleich dem vom angegebenen Objekt dargestellten Wert ist. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine äquivalente Instanz der [Decimal](./) Klasse. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine äquivalente Instanz der [Decimal](./) Klasse unter Verwendung des angegebenen Stils. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine äquivalente Instanz der [Decimal](./) Klasse unter Verwendung des angegebenen Formatproviders. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Konvertiert die Zeichenkettenrepräsentation einer Dezimalzahl in eine äquivalente Instanz der [Decimal](./) Klasse unter Verwendung des angegebenen Stils und Formatproviders. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Berechnet den Rest nach der Division von zwei [Decimal](./) Werten. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf die nächstgelegene ganze Zahl. Ein Parameter legt das Verhalten der Funktion fest, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Rundet den angegebenen Wert auf den nächstgelegenen Wert mit der angegebenen Anzahl von Nachkommastellen. Ein Parameter legt das Verhalten der Funktion fest, wenn der angegebene Wert gleich weit von zwei nächsten Zahlen entfernt ist. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Subtrahiert einen angegebenen [Decimal](./) Wert von einem anderen. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in einen unsigned 8-Bit-Integer-Wert. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in eine double-Genauigkeitsfließkommazahl. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in einen signed 16-Bit-Integer-Wert. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in einen signed 32-Bit-Integer-Wert. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in einen signed 64-Bit-Integer-Wert. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) den angegebenen [Decimal](./) Wert in den entsprechenden OLE-Währungswert. NICHT IMPLEMENTIERT. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in einen signed 8-Bit-Integer-Wert. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in eine single-Genauigkeitsfließkommazahl. |
| std::string [ToStdString](./tostdstring/)() const | Gibt eine Instanz von std::string zurück, die die Zeichenkettenrepräsentation des vom Objekt dargestellten Wertes enthält. |
| [String](../string/) [ToString](./tostring/)() const | Gibt die Zeichenkettenrepräsentation des vom Objekt dargestellten Wertes zurück. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konvertiert das aktuelle Objekt in eine Zeichenkette unter Verwendung der kulturspezifischen Formatinformationen. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konvertiert das aktuelle Objekt in seine Zeichenkettenrepräsentation unter Verwendung des angegebenen Zeichenkettenformats und der kulturspezifischen Formatinformationen, die vom angegebenen [IFormatProvider](../iformatprovider/) Objekt bereitgestellt werden. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Gibt die Zeichenkettenrepräsentation des vom Objekt dargestellten Wertes zurück. Für den internen Gebrauch. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in einen unsigned 16-Bit-Integer-Wert. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in einen unsigned 32-Bit-Integer-Wert. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Konvertiert den [Decimal](./) Wert in einen unsigned 64-Bit-Integer-Wert. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Gibt das [Decimal](./) Objekt zurück, das einen Wert darstellt, dessen ganzzahliger Teil dem des vom angegebenen [Decimal](./) Objekt dargestellten Wertes entspricht, wobei alle Nachkommastellen verworfen wurden. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden [Decimal](./) Wert. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Konvertiert die angegebene Zeichenkette, die die Zeichenkettenrepräsentation einer Zahl enthält, in den entsprechenden [Decimal](./) Wert unter Verwendung der bereitgestellten Formatierungsinformationen und des Zahlenstils. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Gibt eine Referenz auf das [TypeInfo](../typeinfo/) Objekt zurück, das die Typinformation der [Decimal](./) Klasse darstellt. |
| [~Decimal](./~decimal/)() | Destruktor. |

## Felder

| Field | Description |
| --- | --- |
| static [MaxValue](./maxvalue/) | Stellt die größte Zahl dar, die von der [Decimal](./) Klasse dargestellt werden kann. |
| static [MinusOne](./minusone/) | Stellt die Zahl -1 dar. |
| static [MinValue](./minvalue/) | Stellt die kleinste Zahl dar, die von der [Decimal](./) Klasse dargestellt werden kann. |
| static [One](./one/) | Stellt die Zahl 1 dar. |
| static [Zero](./zero/) | Stellt die Zahl 0 dar. |

## Typdefinitionen

| Typedef | Description |
| --- | --- |
| [number_type](./number_type/) | Ein Alias für Detail::decimal_number_type. |

## Bemerkungen

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
Dieses Codebeispiel erzeugt die folgende Ausgabe:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
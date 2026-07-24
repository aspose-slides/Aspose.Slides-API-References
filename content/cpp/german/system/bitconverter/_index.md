---
title: BitConverter
second_title: Aspose.Slides für C++ API-Referenz
description: Enthält Methoden, die Konvertierungen einer Byte-Sequenz in einen Werttyp und umgekehrt durchführen. Es ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 66
url: /de/system/bitconverter/
---
## BitConverter Klasse

Enthält Methoden, die Konvertierungen einer Byte-Sequenz in einen Werttyp und umgekehrt durchführen. Es ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class BitConverter
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Gibt die Endianness der aktuellen Architektur an. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Gibt einen 64-Bit-Integer-Wert zurück, dessen binäre Darstellung der binären Darstellung des angegebenen double-Präzisions-Gleitkommawerts entspricht. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Konvertiert den angegebenen booleschen Wert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Konvertiert den angegebenen char_t-Wert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Konvertiert den angegebenen 16-Bit-Integer-Wert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Konvertiert den angegebenen 32-Bit-Integer-Wert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Konvertiert den angegebenen 64-Bit-Integer-Wert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Konvertiert den angegebenen unsigned 16-Bit-Integer-Wert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Konvertiert den angegebenen unsigned 32-Bit-Integer-Wert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Konvertiert den angegebenen unsigned 64-Bit-Integer-Wert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Konvertiert den angegebenen single-precision Fließkommawert in ein Byte-Array. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Konvertiert den angegebenen double-Präzisions-Fließkommawert in ein Byte-Array. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Gibt einen double-Präzisions-Fließkommawert zurück, dessen Wert dem angegebenen Wert entspricht. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert ein Byte aus dem angegebenen Array, beginnend am angegebenen Index, in einen booleschen Wert. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert ein Byte aus dem angegebenen Array, beginnend am angegebenen Index, in einen booleschen Wert. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen char_t-Wert. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen char_t-Wert. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen double-Präzisions-Fließkommawert. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen double-Präzisions-Fließkommawert. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 16-Bit-Integer-Wert. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 16-Bit-Integer-Wert. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 32-Bit-Integer-Wert. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 32-Bit-Integer-Wert. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 64-Bit-Integer-Wert. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen 64-Bit-Integer-Wert. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen single-precision Fließkommawert. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen single-precision Fließkommawert. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Konvertiert alle Werte des angegebenen Byte-Arrays in deren hexadezimale String-Darstellung. Das zu verwendende Groß-/Kleinschreibungsformat der hexadezimalen Notation und das zwischen benachbarten Bytes eingefügte Trennzeichen werden über die entsprechenden Argumente festgelegt. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert Werte des angegebenen Byte-Arrays in deren hexadezimale String-Darstellung, beginnend am angegebenen Index. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Konvertiert einen Bereich von Werten des angegebenen Byte-Arrays in deren hexadezimale String-Darstellung. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen unsigned 16-Bit-Integer-Wert. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen unsigned 16-Bit-Integer-Wert. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen unsigned 32-Bit-Integer-Wert. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert vier Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen unsigned 32-Bit-Integer-Wert. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen unsigned 64-Bit-Integer-Wert. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konvertiert acht Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen unsigned 64-Bit-Integer-Wert. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Gibt die Endianness der aktuellen Architektur an. true, wenn die Architektur little endian ist, sonst false. |

## Hinweise

```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Erstelle Werte zum Ausgeben.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Wert und seine Bytes ausgeben.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
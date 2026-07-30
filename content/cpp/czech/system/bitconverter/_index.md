---
title: BitConverter
second_title: Aspose.Slides pro C++ referenční příručka API
description: Obsahuje metody, které provádějí konverze sekvence bajtů na hodnotový typ a naopak. Jedná se o statický typ bez instančních služeb. Nikdy byste jej neměli vytvářet jako instanci žádným způsobem.
type: docs
weight: 66
url: /cs/system/bitconverter/
---
## BitConverter třída

Obsahuje metody, které provádějí konverze sekvence bajtů na hodnotový typ a naopak. Jedná se o statický typ bez instančních služeb. Nikdy byste jej neměli vytvářet jako instanci žádným způsobem.

```cpp
class BitConverter
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Udává endianitu aktuální architektury. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Vrací 64-bitovou celočíselnou hodnotu, jejíž binární reprezentace je shodná s binární reprezentací zadané hodnoty s dvojitou přesností. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Převádí zadanou boolean hodnotu do pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Převádí zadanou hodnotu typu char_t na pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Převádí zadanou 16-bitovou celočíselnou hodnotu na pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Převádí zadanou 32-bitovou celočíselnou hodnotu na pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Převádí zadanou 64-bitovou celočíselnou hodnotu na pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Převádí zadanou unsigned 16-bitovou celočíselnou hodnotu na pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Převádí zadanou unsigned 32-bitovou celočíselnou hodnotu na pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Převádí zadanou unsigned 64-bitovou celočíselnou hodnotu na pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Převádí zadanou single-precision floating-point hodnotu na pole bajtů. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Převádí zadanou double-precision floating-point hodnotu na pole bajtů. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Vrací double-precision floating-point hodnotu, jejíž hodnota je ekvivalentní vstupní hodnotě. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí jeden bajt ze zadaného pole počínaje zadaným indexem na boolean hodnotu. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí jeden bajt ze zadaného pole počínaje zadaným indexem na boolean hodnotu. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí dva bajty ze zadaného pole počínaje zadaným indexem na char_t hodnotu. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí dva bajty ze zadaného pole počínaje zadaným indexem na char_t hodnotu. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na double-precision floating-point hodnotu. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na double-precision floating-point hodnotu. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí dva bajty ze zadaného pole počínaje zadaným indexem na 16-bitovou celočíselnou hodnotu. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí dva bajty ze zadaného pole počínaje zadaným indexem na 16-bitovou celočíselnou hodnotu. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na 32-bitovou celočíselnou hodnotu. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na 32-bitovou celočíselnou hodnotu. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na 64-bitovou celočíselnou hodnotu. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na 64-bitovou celočíselnou hodnotu. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na single-precision floating-point hodnotu. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na single-precision floating-point hodnotu. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Převádí všechny hodnoty zadaného pole bajtů do jejich hexadecimální řetězcové reprezentace. Velikost písmen použité v hexadecimální notaci a oddělovač vložený mezi každou dvojici sousedních bajtů jsou specifikovány odpovídajícími argumenty. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí hodnoty zadaného pole bajtů do jejich hexadecimální řetězcové reprezentace počínaje zadaným indexem. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Převádí rozsah hodnot zadaného pole bajtů do jejich hexadecimální řetězcové reprezentace. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí dva bajty ze zadaného pole počínaje zadaným indexem na unsigned 16-bitovou celočíselnou hodnotu. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí dva bajty ze zadaného pole počínaje zadaným indexem na unsigned 16-bitovou celočíselnou hodnotu. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na unsigned 32-bitovou celočíselnou hodnotu. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí čtyři bajty ze zadaného pole počínaje zadaným indexem na unsigned 32-bitovou celočíselnou hodnotu. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na unsigned 64-bitovou celočíselnou hodnotu. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Převádí osm bajtů ze zadaného pole počínaje zadaným indexem na unsigned 64-bitovou celočíselnou hodnotu. |

## Pole

| Pole | Popis |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Udává endianitu aktuální architektury. true pokud je architektura little endian, false jinak. |

## Poznámky

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
  // Vytvořte hodnoty k vytištění.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Vytiskněte hodnotu a její bajty.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Tento ukázkový kód produkuje následující výstup:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)
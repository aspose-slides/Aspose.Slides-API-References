---
title: BitConverter
second_title: Aspose.Slides voor C++ API-referentie
description: Bevat methoden die conversies uitvoeren van een reeks bytes naar een waardetype en omgekeerd. Dit is een statisch type zonder instantie services. Je mag nooit instanties ervan maken op welke manier dan ook.
type: docs
weight: 66
url: /nl/system/bitconverter/
---
## BitConverter klasse

Bevat methoden die conversies uitvoeren van een reeks bytes naar een waardetype en omgekeerd. Dit is een statisch type zonder instantie services. Je zou nooit instanties ervan moeten maken op welke manier dan ook.

```cpp
class BitConverter
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Geeft de endian-orde van de huidige architectuur aan. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Retourneert een 64-bit geheel getal waarvan de binaire representatie gelijk is aan de binaire representatie van de opgegeven double-precision floating point-waarde. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Converteert de opgegeven booleaanse waarde naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Converteert de opgegeven char_t-waarde naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Converteert de opgegeven 16-bit geheel getal naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Converteert de opgegeven 32-bit geheel getal naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Converteert de opgegeven 64-bit geheel getal naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Converteert de opgegeven ongetekende 16-bit geheel getal naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Converteert de opgegeven ongetekende 32-bit geheel getal naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Converteert de opgegeven ongetekende 64-bit geheel getal naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Converteert de opgegeven single-precision floating-point-waarde naar een array van bytes. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Converteert de opgegeven double-precision floating-point-waarde naar een array van bytes. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Retourneert een double-precision floating point-waarde waarvan de waarde gelijk is aan value. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert één byte uit de opgegeven array beginnend bij de opgegeven index naar een booleaanse waarde. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert één byte uit de opgegeven array beginnend bij de opgegeven index naar een booleaanse waarde. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert twee bytes uit de opgegeven array beginnend bij de opgegeven index naar een char_t-waarde. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert twee bytes uit de opgegeven array beginnend bij de opgegeven index naar een char_t-waarde. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert acht bytes uit de opgegeven array beginnend bij de opgegeven index naar een double-precision floating point-waarde. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert acht bytes uit de opgegeven array beginnend bij de opgegeven index naar een double-precision floating point-waarde. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert twee bytes uit de opgegeven array beginnend bij de opgegeven index naar een 16-bit geheel getal. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert twee bytes uit de opgegeven array beginnend bij de opgegeven index naar een 16-bit geheel getal. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert vier bytes uit de opgegeven array beginnend bij de opgegeven index naar een 32-bit geheel getal. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert vier bytes uit de opgegeven array beginnend bij de opgegeven index naar een 32-bit geheel getal. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert acht bytes uit de opgegeven array beginnend bij de opgegeven index naar een 64-bit geheel getal. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert acht bytes uit de opgegeven array beginnend bij de opgegeven index naar een 64-bit geheel getal. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert vier bytes uit de opgegeven array beginnend bij de opgegeven index naar een single-precision floating point-waarde. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert vier bytes uit de opgegeven array beginnend bij de opgegeven index naar een single-precision floating point-waarde. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Converteert alle waarden van de opgegeven byte-array naar hun hexadecimale tekenreeksrepresentatie. Hoofdlettergebruik voor letters in de hexadecimale notatie en de scheidingsteken die tussen elk paar naast elkaar liggende bytes wordt ingevoegd, worden gespecificeerd via de overeenkomstige argumenten. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert waarden van de opgegeven byte-array naar hun hexadecimale tekenreeksrepresentatie beginnend bij de opgegeven index. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Converteert een bereik van waarden van de opgegeven byte-array naar hun hexadecimale tekenreeksrepresentatie. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert twee bytes uit de opgegeven array beginnend bij de opgegeven index naar een ongetekende 16-bit geheel getal. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert twee bytes uit de opgegeven array beginnend bij de opgegeven index naar een ongetekende 16-bit geheel getal. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert vier bytes uit de opgegeven array beginnend bij de opgegeven index naar een ongetekende 32-bit geheel getal. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert vier bytes uit de opgegeven array beginnend bij de opgegeven index naar een ongetekende 32-bit geheel getal. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Converteert acht bytes uit de opgegeven array beginnend bij de opgegeven index naar een ongetekende 64-bit geheel getal. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Converteert acht bytes uit de opgegeven array beginnend bij de opgegeven index naar een ongetekende 64-bit geheel getal. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Geeft de endian-orde van de huidige architectuur aan. true als de architectuur little endian is, false anders. |

## Opmerkingen



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
  // Maak waarden om af te drukken.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Print de waarde en de bytes.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Zie ook

* naamruimte [System](../)
* bibliotheek [Aspose.Slides](../../)
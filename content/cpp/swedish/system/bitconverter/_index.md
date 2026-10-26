---
title: BitConverter
second_title: Aspose.Slides för C++ API-referens
description: Innehåller metoder som utför konverteringar av en sekvens av byte till en värdetyp och vice-versa. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 66
url: /sv/system/bitconverter/
---
## BitConverter klass

Innehåller metoder som utför konverteringar av en sekvens av byte till en värdetyp och vice-versa. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class BitConverter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Indikerar byteordningen för den aktuella arkitekturen. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Returnerar ett 64-bit heltal vars binära representation är lika med den binära representationen av det angivna dubbelprecision flyttal. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Konverterar det angivna booleska värdet till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Konverterar det angivna char_t-värdet till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Konverterar det angivna 16-bit heltalet till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Konverterar det angivna 32-bit heltalet till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Konverterar det angivna 64-bit heltalet till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Konverterar det angivna unsigned 16-bit heltalet till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Konverterar det angivna unsigned 32-bit heltalet till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Konverterar det angivna unsigned 64-bit heltalet till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Konverterar det angivna single-precision flyttal till en bytearray. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Konverterar det angivna dubbelprecision flyttal till en bytearray. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Returnerar ett dubbelprecision flyttal vars värde är ekvivalent med det angivna värdet. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar en byte från den angivna arrayen vid den specificerade indexpositionen till ett booleskt värde. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar en byte från den angivna arrayen vid den specificerade indexpositionen till ett booleskt värde. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar två byte från den angivna arrayen vid den specificerade indexpositionen till ett char_t-värde. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar två byte från den angivna arrayen vid den specificerade indexpositionen till ett char_t-värde. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar åtta byte från den angivna arrayen vid den specificerade indexpositionen till ett dubbelprecision flyttal. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar åtta byte från den angivna arrayen vid den specificerade indexpositionen till ett dubbelprecision flyttal. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar två byte från den angivna arrayen vid den specificerade indexpositionen till ett 16-bit heltal. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar två byte från den angivna arrayen vid den specificerade indexpositionen till ett 16-bit heltal. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar fyra byte från den angivna arrayen vid den specificerade indexpositionen till ett 32-bit heltal. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar fyra byte från den angivna arrayen vid den specificerade indexpositionen till ett 32-bit heltal. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar åtta byte från den angivna arrayen vid den specificerade indexpositionen till ett 64-bit heltal. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar åtta byte från den angivna arrayen vid den specificerade indexpositionen till ett 64-bit heltal. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar fyra byte från den angivna arrayen vid den specificerade indexpositionen till ett single-precision flyttal. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar fyra byte från den angivna arrayen vid den specificerade indexpositionen till ett single-precision flyttal. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Konverterar alla värden i den angivna bytearrayen till deras hexadecimala strängrepresentation. Storlek på bokstäver och separator mellan intilliggande bytepar anges via motsvarande argument. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar värden i den angivna bytearrayen till deras hexadecimala strängrepresentation med start på angivet index. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Konverterar ett intervall av värden i den angivna bytearrayen till deras hexadecimala strängrepresentation. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar två byte från den angivna arrayen vid den specificerade indexpositionen till ett unsigned 16-bit heltal. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar två byte från den angivna arrayen vid den specificerade indexpositionen till ett unsigned 16-bit heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar fyra byte från den angivna arrayen vid den specificerade indexpositionen till ett unsigned 32-bit heltal. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar fyra byte från den angivna arrayen vid den specificerade indexpositionen till ett unsigned 32-bit heltal. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Konverterar åtta byte från den angivna arrayen vid den specificerade indexpositionen till ett unsigned 64-bit heltal. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Konverterar åtta byte från den angivna arrayen vid den specificerade indexpositionen till ett unsigned 64-bit heltal. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Indikerar byteordningen för den aktuella arkitekturen. true om arkitekturen är little endian, false annars. |
## Anmärkningar



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
  // Skapa värden att skriva ut.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Skriv ut värdet och dess byte.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Detta kodexempel ger följande utdata:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
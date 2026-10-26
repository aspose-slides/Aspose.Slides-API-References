---
title: BitConverter
second_title: Aspose.Slides C++ API hivatkozás
description: Tartalmaz olyan metódusokat, amelyek a bájtok sorozatát értéktípusra és fordítva konvertálják. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha ne hozzon létre példányt ebből semmilyen módon.
type: docs
weight: 66
url: /hu/system/bitconverter/
---
## BitConverter osztály

Tartalmaz olyan metódusokat, amelyek a bájtok sorozatát értéktípusra és fordítva konvertálják. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha ne hozzon létre példányt ebből semmilyen módon.

```cpp
class BitConverter
```

## Metódusok

| Method | Description |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Jelzi a jelenlegi architektúra endianitását. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Visszaad egy 64 bites egész értéket, amelynek bináris reprezentációja megegyezik a megadott dupla pontosságú lebegőpontos érték bináris reprezentációjával. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Átalakítja a megadott logikai értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Átalakítja a megadott char_t értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Átalakítja a megadott 16 bites egész értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Átalakítja a megadott 32 bites egész értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Átalakítja a megadott 64 bites egész értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Átalakítja a megadott előjel nélküli 16 bites egész értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Átalakítja a megadott előjel nélküli 32 bites egész értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Átalakítja a megadott előjel nélküli 64 bites egész értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Átalakítja a megadott egyszeres pontosságú lebegőpontos értéket bájt tömbbé. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Átalakítja a megadott dupla pontosságú lebegőpontos értéket bájt tömbbé. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Visszaad egy dupla pontosságú lebegőpontos értéket, amelynek értéke megegyezik a megadott értékkel. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít egy bájtot a megadott tömbből a megadott indexnél logikai értékké. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít egy bájtot a megadott tömbből a megadott indexnél logikai értékké. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít két bájtot a megadott tömbből a megadott indexnél char_t értékké. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít két bájtot a megadott tömbből a megadott indexnél char_t értékké. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít nyolc bájtot a megadott tömbből a megadott indexnél dupla pontosságú lebegőpontos értékké. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít nyolc bájtot a megadott tömbből a megadott indexnél dupla pontosságú lebegőpontos értékké. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít két bájtot a megadott tömbből a megadott indexnél 16 bites egész értékké. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít két bájtot a megadott tömbből a megadott indexnél 16 bites egész értékké. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít négy bájtot a megadott tömbből a megadott indexnél 32 bites egész értékké. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít négy bájtot a megadott tömbből a megadott indexnél 32 bites egész értékké. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít nyolc bájtot a megadott tömbből a megadott indexnél 64 bites egész értékké. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít nyolc bájtot a megadott tömbből a megadott indexnél 64 bites egész értékké. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít négy bájtot a megadott tömbből a megadott indexnél egyszeres pontosságú lebegőpontos értékké. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít négy bájtot a megadott tömbből a megadott indexnél egyszeres pontosságú lebegőpontos értékké. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Átalakítja a megadott bájt tömb összes értékét hexadecimális karakterlánc ábrázolásává. A hexadecimális notációban használandó betűk nagybetű/kisbetű esete és a szomszédos bájtok között beillesztett elválasztó a megfelelő argumentumokkal adható meg. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakítja a megadott bájt tömb értékeit hexadecimális karakterlánc ábrázolásává a megadott indextől kezdve. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Átalakítja a megadott bájt tömb egy tartományának értékeit hexadecimális karakterlánc ábrázolásává. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít két bájtot a megadott tömbből a megadott indexnél előjel nélküli 16 bites egész értékké. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít két bájtot a megadott tömbből a megadott indexnél előjel nélküli 16 bites egész értékké. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít négy bájtot a megadott tömbből a megadott indexnél előjel nélküli 32 bites egész értékké. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít négy bájtot a megadott tömbből a megadott indexnél előjel nélküli 32 bites egész értékké. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Átalakít nyolc bájtot a megadott tömbből a megadott indexnél előjel nélküli 64 bites egész értékké. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Átalakít nyolc bájtot a megadott tömbből a megadott indexnél előjel nélküli 64 bites egész értékké. |

## Mezők

| Field | Description |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Jelzi a jelenlegi architektúra endianitását. true, ha az architektúra kisvégű, false egyébként. |

## Megjegyzések



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
  // Létrehozza a kiírandó értékeket.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Kiírja az értéket és a bájtjait.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Ez a kódpélda a következő kimenetet állítja elő:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)
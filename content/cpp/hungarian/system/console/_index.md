---
title: Console
second_title: Aspose.Slides for C++ API Referencia
description: Metódusokat biztosít az adatok szabványos kimeneti áramra írásához. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha nem szabad példányokat létrehozni belőle semmilyen módon.
type: docs
weight: 196
url: /hu/system/console/
---
## Console osztály

Biztosítja a standard kimeneti áramra történő adatkiírás metódusait. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha nem szabad példányokat létrehozni ebből semmilyen módon.

```cpp
class Console
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static void [Beep](./beep/)() | NEM IMPLEMENTÁLVA. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Visszaad egy megosztott mutatót, amely a szabványos hibakimeneti áramot képviselő objektumra mutat. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Visszaad egy megosztott mutatót, amely a szabványos bemeneti áramot képviselő objektumra mutat. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Visszaad egy megosztott mutatót, amely a szabványos kimeneti áramot képviselő objektumra mutat. |
| static void [Mute](./mute/)(**bool**) | Némítja vagy visszakapcsolja a szabványos kimeneti áramot. |
| static void [ReadKey](./readkey/)() | NEM IMPLEMENTÁLVA. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Beállítja a konzol ablak feliratát. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | A megadott objektumot a osztály Error tulajdonságához rendeli. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Beállítja az In tulajdonságot a megadott TextReader objektumra. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | A megadott objektumot az osztály Out tulajdonságához rendeli. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Kiírja a megadott objektum karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(**bool**) | Kiírja a bool érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(char_t) | Kiírja a megadott karakterértéket a szabványos kimeneti áramra. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Kiírja a megadott karaktertömb karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Kiírja a [Decimal](../decimal/) érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(**double**) | Kiírja a dupla pontosságú lebegőpontos érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(**float**) | Kiírja az egyszeres pontosságú lebegőpontos érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(**int32_t**) | Kiírja a 32 bites egész szám érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(**int64_t**) | Kiírja a 64 bites egész szám érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(const [String](../string/)\&) | Kiírja a megadott karakterlánc objektumot a szabványos kimeneti áramra. |
| static void [Write](./write/)(const char_t *) | Kiírja a megadott c-karakterláncot a szabványos kimeneti áramra. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Kiírja a [TypeInfo](../typeinfo/) érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(**uint32_t**) | Kiírja az előjel nélküli 32 bites egész szám érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(**uint64_t**) | Kiírja az előjel nélküli 64 bites egész szám érték karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Kiírja a megadott karaktertömb megadott tartományának karakterlánc ábrázolását a szabványos kimeneti áramra. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Kiírja a megadott argumentumok formázott karakterlánc ábrázolását a megadott formátum szerint a szabványos kimeneti áramra. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Kiírja az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Kiírja a megadott objektum karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(**bool**) | Kiírja a bool érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(char_t) | Kiírja a megadott karakterértéket, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Kiírja a megadott karaktertömb karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Kiírja a [Decimal](../decimal/) érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(**double**) | Kiírja a dupla pontosságú lebegőpontos érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(**float**) | Kiírja az egyszeres pontosságú lebegőpontos érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(**int32_t**) | Kiírja a 32 bites egész szám érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(**int64_t**) | Kiírja a 64 bites egész szám érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Kiírja a megadott karakterlánc objektumot, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const char_t *) | Kiírja a megadott c-karakterláncot, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Kiírja a [TypeInfo](../typeinfo/) érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Kiírja az előjel nélküli 32 bites egész szám érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Kiírja az előjel nélküli 64 bites egész szám érték karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Kiírja a megadott karaktertömb megadott tartományának karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Kiírja a megadott Exception objektum karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Kiírja a megadott argumentumok, a megadott formátum szerint formázott karakterlánc ábrázolását, majd az aktuális sorvégződést a szabványos kimeneti áramra. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Megjegyzések

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Kiírja az üdvözlő üzenetet.
  Console::WriteLine(u"Hello, world!");

  // Létrehoz egy példányt a 'std::array' osztályból.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Kiírja a tömb elemeit.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Ez a kódpélda a következő kimenetet állítja elő:
Hello, world!
1 2 3 4 5
*/
```

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)
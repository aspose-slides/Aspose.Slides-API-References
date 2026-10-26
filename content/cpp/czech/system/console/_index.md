---
title: Console
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje metody pro výstup dat do standardního výstupního proudu. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem.
type: docs
weight: 196
url: /cs/system/console/
---
## Console třída

Poskytuje metody pro výstup dat do standardního výstupního proudu. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance žádným způsobem.

```cpp
class Console
```

## Metody

| Method | Description |
| --- | --- |
| static void [Beep](./beep/)() | NEIMPLEMENTOVÁNO. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Vrací sdílený ukazatel směřující na objekt, který představuje standardní chybový proud. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Vrací sdílený ukazatel směřující na objekt, který představuje standardní vstupní proud. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Vrací sdílený ukazatel směřující na objekt, který představuje standardní výstupní proud. |
| static void [Mute](./mute/)(**bool**) | Ztlumí nebo zruší ztlumení standardního výstupního proudu. |
| static void [ReadKey](./readkey/)() | NEIMPLEMENTOVÁNO. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Nastavuje titulek okna konzoly. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Přiřazuje zadaný objekt do vlastnosti Error třídy. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Nastavuje vlastnost In na zadaný objekt TextReader. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Přiřazuje zadaný objekt do vlastnosti Out třídy. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Vypíše řetězcovou reprezentaci zadaného objektu do standardního výstupního proudu. |
| static void [Write](./write/)(**bool**) | Vypíše řetězcovou reprezentaci hodnoty bool do standardního výstupního proudu. |
| static void [Write](./write/)(char_t) | Vypíše zadanou znakovou hodnotu do standardního výstupního proudu. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Vypíše řetězcovou reprezentaci zadaného pole znaků do standardního výstupního proudu. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Vypíše řetězcovou reprezentaci hodnoty [Decimal](../decimal/) do standardního výstupního proudu. |
| static void [Write](./write/)(**double**) | Vypíše řetězcovou reprezentaci dvojité přesnosti s plovoucí desetinnou čárkou do standardního výstupního proudu. |
| static void [Write](./write/)(**float**) | Vypíše řetězcovou reprezentaci jednoduché přesnosti s plovoucí desetinnou čárkou do standardního výstupního proudu. |
| static void [Write](./write/)(**int32_t**) | Vypíše řetězcovou reprezentaci 32bitové celočíselné hodnoty do standardního výstupního proudu. |
| static void [Write](./write/)(**int64_t**) | Vypíše řetězcovou reprezentaci 64bitové celočíselné hodnoty do standardního výstupního proudu. |
| static void [Write](./write/)(const [String](../string/)\&) | Vypíše zadaný řetězcový objekt do standardního výstupního proudu. |
| static void [Write](./write/)(const char_t *) | Vypíše zadaný C-řetězec do standardního výstupního proudu. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Vypíše řetězcovou reprezentaci hodnoty [TypeInfo](../typeinfo/) do standardního výstupního proudu. |
| static void [Write](./write/)(**uint32_t**) | Vypíše řetězcovou reprezentaci nezáporné 32bitové celočíselné hodnoty do standardního výstupního proudu. |
| static void [Write](./write/)(**uint64_t**) | Vypíše řetězcovou reprezentaci nezáporné 64bitové celočíselné hodnoty do standardního výstupního proudu. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Vypíše řetězcovou reprezentaci zadaného rozsahu zadaného pole znaků do standardního výstupního proudu. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Vypíše řetězcovou reprezentaci zadaných argumentů formátovaných podle zadaného formátu do standardního výstupního proudu. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Vypíše aktuální ukončovač řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Vypíše řetězcovou reprezentaci zadaného objektu následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(**bool**) | Vypíše řetězcovou reprezentaci hodnoty bool následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(char_t) | Vypíše zadanou znakovou hodnotu následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Vypíše řetězcovou reprezentaci zadaného pole znaků následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Vypíše řetězcovou reprezentaci hodnoty [Decimal](../decimal/) následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(**double**) | Vypíše řetězcovou reprezentaci dvojité přesnosti s plovoucí desetinnou čárkou následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(**float**) | Vypíše řetězcovou reprezentaci jednoduché přesnosti s plovoucí desetinnou čárkou následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(**int32_t**) | Vypíše řetězcovou reprezentaci 32bitové celočíselné hodnoty následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(**int64_t**) | Vypíše řetězcovou reprezentaci 64bitové celočíselné hodnoty následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Vypíše zadaný řetězcový objekt následovaný aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const char_t *) | Vypíše zadaný C-řetězec následovaný aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Vypíše řetězcovou reprezentaci hodnoty [TypeInfo](../typeinfo/) následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Vypíše řetězcovou reprezentaci nezáporné 32bitové celočíselné hodnoty následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Vypíše řetězcovou reprezentaci nezáporné 64bitové celočíselné hodnoty následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Vypíše řetězcovou reprezentaci zadaného rozsahu zadaného pole znaků následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Vypíše řetězcovou reprezentaci zadaného objektu Exception následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Vypíše řetězcovou reprezentaci zadaných argumentů formátovaných podle zadaného formátu následovanou aktuálním ukončovačem řádku do standardního výstupního proudu. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Poznámky

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Vytiskne uvítací zprávu.
  Console::WriteLine(u"Hello, world!");

  // Vytvoří instanci třídy 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Vytiskne prvky pole.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Tento příklad kódu vytváří následující výstup:
Hello, world!
1 2 3 4 5
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)
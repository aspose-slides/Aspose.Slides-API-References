---
title: Console
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller metoder för att skriva ut data till standardutgångsströmmen. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.
type: docs
weight: 196
url: /sv/system/console/
---
## Console-klass


Tillhandahåller metoder för att skriva ut data till standardutgångsströmmen. Detta är en statisk typ utan instansfunktioner. Du bör aldrig skapa instanser av den på något sätt.

```cpp
class Console
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static void [Beep](./beep/)() | INTE IMPLEMENTERAD. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Returnerar en delad pekare som pekar på objektet som representerar standardfelströmmen. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Returnerar en delad pekare som pekar på objektet som representerar standardinmatningsströmmen. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Returnerar en delad pekare som pekar på objektet som representerar standardutgångsströmmen. |
| static void [Mute](./mute/)(**bool**) | Dämpar eller återaktiverar standardutgångsströmmen. |
| static void [ReadKey](./readkey/)() | INTE IMPLEMENTERAD. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Ställer in rubriken för konsolfönstret. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Tilldelar det angivna objektet till klassens Error-egenskap. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Sätter In-egenskapen till det angivna TextReader-objektet. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Tilldelar det angivna objektet till klassens Out-egenskap. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Skriver ut strängrepresentationen av det angivna objektet till standardutgångsströmmen. |
| static void [Write](./write/)(**bool**) | Skriver ut strängrepresentationen av bool-värdet till standardutgångsströmmen. |
| static void [Write](./write/)(char_t) | Skriver ut det angivna teckenvärdet till standardutgångsströmmen. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Skriver ut strängrepresentationen av den angivna teckenarrayen till standardutgångsströmmen. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Skriver ut strängrepresentationen av [Decimal](../decimal/)-värdet till standardutgångsströmmen. |
| static void [Write](./write/)(**double**) | Skriver ut strängrepresentationen av dubbelprecision flyttal till standardutgångsströmmen. |
| static void [Write](./write/)(**float**) | Skriver ut strängrepresentationen av enkelprecision flyttal till standardutgångsströmmen. |
| static void [Write](./write/)(**int32_t**) | Skriver ut strängrepresentationen av 32-bitars heltal till standardutgångsströmmen. |
| static void [Write](./write/)(**int64_t**) | Skriver ut strängrepresentationen av 64-bitars heltal till standardutgångsströmmen. |
| static void [Write](./write/)(const [String](../string/)\&) | Skriver ut det angivna strängobjektet till standardutgångsströmmen. |
| static void [Write](./write/)(const char_t *) | Skriver ut den angivna C-strängen till standardutgångsströmmen. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Skriver ut strängrepresentationen av [TypeInfo](../typeinfo/)-värdet till standardutgångsströmmen. |
| static void [Write](./write/)(**uint32_t**) | Skriver ut strängrepresentationen av 32-bitars osignerat heltal till standardutgångsströmmen. |
| static void [Write](./write/)(**uint64_t**) | Skriver ut strängrepresentationen av 64-bitars osignerat heltal till standardutgångsströmmen. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Skriver ut strängrepresentationen av det angivna intervallet i den angivna teckenarrayen till standardutgångsströmmen. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Skriver ut strängrepresentationen av de angivna argumenten formaterade enligt det angivna formatet till standardutgångsströmmen. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Skriver ut den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Skriver ut strängrepresentationen av det angivna objektet följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(**bool**) | Skriver ut strängrepresentationen av bool-värdet följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(char_t) | Skriver ut det angivna teckenvärdet följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Skriver ut strängrepresentationen av den angivna teckenarrayen följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Skriver ut strängrepresentationen av [Decimal](../decimal/)-värdet följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(**double**) | Skriver ut strängrepresentationen av dubbelprecision flyttal följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(**float**) | Skriver ut strängrepresentationen av enkelprecision flyttal följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(**int32_t**) | Skriver ut strängrepresentationen av 32-bitars heltal följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(**int64_t**) | Skriver ut strängrepresentationen av 64-bitars heltal följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Skriver ut det angivna strängobjektet följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const char_t *) | Skriver ut den angivna C-strängen följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Skriver ut strängrepresentationen av [TypeInfo](../typeinfo/)-värdet följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Skriver ut strängrepresentationen av 32-bitars osignerat heltal följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Skriver ut strängrepresentationen av 64-bitars osignerat heltal följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Skriver ut strängrepresentationen av det angivna intervallet i den angivna teckenarrayen följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Skriver ut strängrepresentationen av det angivna Exception-objektet följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Skriver ut strängrepresentationen av de angivna argumenten formaterade enligt det angivna formatet följt av den aktuella radavslutaren till standardutgångsströmmen. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Anmärkningar



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Skriv ut hälsningsmeddelandet.
  Console::WriteLine(u"Hello, world!");

  // Skapa en instans av klassen 'std::array' class.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Skriv ut elementen i arrayen.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Detta kodexempel producerar följande utdata:
Hej, världen!
1 2 3 4 5
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
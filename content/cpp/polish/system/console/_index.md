---
title: Console
second_title: Odwołanie do API Aspose.Slides dla C++
description: Udostępnia metody do wypisywania danych na standardowy strumień wyjściowy. Jest to typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.
type: docs
weight: 196
url: /pl/system/console/
---
## Klasa Console

Udostępnia metody do wypisywania danych na standardowy strumień wyjściowy. Jest to typ statyczny bez usług instancji. Nie powinieneś nigdy tworzyć jego instancji w żaden sposób.

```cpp
class Console
```

## Metody

| Metoda | Opis |
| --- | --- |
| static void [Beep](./beep/)() | NIE ZAIMPLEMENTOWANO. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Zwraca współdzielony wskaźnik wskazujący na obiekt reprezentujący standardowy strumień błędów. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Zwraca współdzielony wskaźnik wskazujący na obiekt reprezentujący standardowy strumień wejściowy. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Zwraca współdzielony wskaźnik wskazujący na obiekt reprezentujący standardowy strumień wyjściowy. |
| static void [Mute](./mute/)(**bool**) | Wycisza lub włącza dźwięk standardowego strumienia wyjściowego. |
| static void [ReadKey](./readkey/)() | NIE ZAIMPLEMENTOWANO. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Ustawia tytuł okna konsoli. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Przypisuje określony obiekt do właściwości Error klasy. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Ustawia właściwość In na określony obiekt TextReader. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Przypisuje określony obiekt do właściwości Out klasy. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Wypisuje reprezentację łańcuchową określonego obiektu na standardowy strumień wyjściowy. |
| static void [Write](./write/)(**bool**) | Wypisuje reprezentację łańcuchową wartości bool na standardowy strumień wyjściowy. |
| static void [Write](./write/)(char_t) | Wypisuje określoną wartość znaku na standardowy strumień wyjściowy. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Wypisuje reprezentację łańcuchową określonej tablicy znaków na standardowy strumień wyjściowy. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Wypisuje reprezentację łańcuchową wartości [Decimal](../decimal/) na standardowy strumień wyjściowy. |
| static void [Write](./write/)(**double**) | Wypisuje reprezentację łańcuchową wartości zmiennoprzecinkowej podwójnej precyzji na standardowy strumień wyjściowy. |
| static void [Write](./write/)(**float**) | Wypisuje reprezentację łańcuchową wartości zmiennoprzecinkowej pojedynczej precyzji na standardowy strumień wyjściowy. |
| static void [Write](./write/)(**int32_t**) | Wypisuje reprezentację łańcuchową 32-bitowej wartości całkowitej na standardowy strumień wyjściowy. |
| static void [Write](./write/)(**int64_t**) | Wypisuje reprezentację łańcuchową 64-bitowej wartości całkowitej na standardowy strumień wyjściowy. |
| static void [Write](./write/)(const [String](../string/)\&) | Wypisuje określony obiekt łańcuchowy na standardowy strumień wyjściowy. |
| static void [Write](./write/)(const char_t *) | Wypisuje określony ciąg C na standardowy strumień wyjściowy. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Wypisuje reprezentację łańcuchową wartości [TypeInfo](../typeinfo/) na standardowy strumień wyjściowy. |
| static void [Write](./write/)(**uint32_t**) | Wypisuje reprezentację łańcuchową nieznakowanej 32-bitowej wartości całkowitej na standardowy strumień wyjściowy. |
| static void [Write](./write/)(**uint64_t**) | Wypisuje reprezentację łańcuchową nieznakowanej 64-bitowej wartości całkowitej na standardowy strumień wyjściowy. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Wypisuje reprezentację łańcuchową określonego zakresu określonej tablicy znaków na standardowy strumień wyjściowy. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Wypisuje reprezentację łańcuchową określonych argumentów sformatowanych zgodnie z podanym formatem na standardowy strumień wyjściowy. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Wypisuje bieżący znak zakończenia linii na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Wypisuje reprezentację łańcuchową określonego obiektu, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(**bool**) | Wypisuje reprezentację łańcuchową wartości bool, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(char_t) | Wypisuje określoną wartość znaku, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Wypisuje reprezentację łańcuchową określonej tablicy znaków, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Wypisuje reprezentację łańcuchową wartości [Decimal](../decimal/), po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(**double**) | Wypisuje reprezentację łańcuchową wartości zmiennoprzecinkowej podwójnej precyzji, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(**float**) | Wypisuje reprezentację łańcuchową wartości zmiennoprzecinkowej pojedynczej precyzji, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(**int32_t**) | Wypisuje reprezentację łańcuchową 32-bitowej wartości całkowitej, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(**int64_t**) | Wypisuje reprezentację łańcuchową 64-bitowej wartości całkowitej, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Wypisuje określony obiekt łańcuchowy, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const char_t *) | Wypisuje określony ciąg C, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Wypisuje reprezentację łańcuchową wartości [TypeInfo](../typeinfo/), po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Wypisuje reprezentację łańcuchową nieznakowanej 32-bitowej wartości całkowitej, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Wypisuje reprezentację łańcuchową nieznakowanej 64-bitowej wartości całkowitej, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Wypisuje reprezentację łańcuchową określonego zakresu określonej tablicy znaków, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Wypisuje reprezentację łańcuchową określonego obiektu Exception, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Wypisuje reprezentację łańcuchową określonych argumentów sformatowanych zgodnie z podanym formatem, po której następuje bieżący znak zakończenia linii, na standardowy strumień wyjściowy. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Uwagi



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Wypisz komunikat powitalny.
  Console::WriteLine(u"Hello, world!");

  // Utwórz instancję klasy 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Wypisz elementy tablicy.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
Hello, world!
1 2 3 4 5
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)
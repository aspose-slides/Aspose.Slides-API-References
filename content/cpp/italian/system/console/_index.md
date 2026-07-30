---
title: Console
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce metodi per l'output di dati sullo stream di output standard. Si tratta di un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.
type: docs
weight: 196
url: /it/system/console/
---
## Console classe


Fornisce metodi per l'output di dati sullo stream di output standard. Si tratta di un tipo statico senza servizi di istanza. Non dovresti mai creare istanze di esso in alcun modo.

```cpp
class Console
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static void [Beep](./beep/)() | NON IMPLEMENTATO. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Restituisce un puntatore condiviso che punta all'oggetto che rappresenta lo stream di errore standard. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Restituisce un puntatore condiviso che punta all'oggetto che rappresenta lo stream di input standard. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Restituisce un puntatore condiviso che punta all'oggetto che rappresenta lo stream di output standard. |
| static void [Mute](./mute/)(**bool**) | Silenzia o riattiva lo stream di output standard. |
| static void [ReadKey](./readkey/)() | NON IMPLEMENTATO. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Imposta la didascalia della finestra della console. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Assegna l'oggetto specificato alla proprietà Error della classe. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Imposta la proprietà In sull'oggetto TextReader specificato. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Assegna l'oggetto specificato alla proprietà Out della classe. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Stampa la rappresentazione stringa dell'oggetto specificato sullo stream di output standard. |
| static void [Write](./write/)(**bool**) | Stampa la rappresentazione stringa del valore bool sullo stream di output standard. |
| static void [Write](./write/)(char_t) | Stampa il valore carattere specificato sullo stream di output standard. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Stampa la rappresentazione stringa dell'array di caratteri specificato sullo stream di output standard. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Stampa la rappresentazione stringa del valore [Decimal](../decimal/) sullo stream di output standard. |
| static void [Write](./write/)(**double**) | Stampa la rappresentazione stringa del valore a virgola mobile a doppia precisione sullo stream di output standard. |
| static void [Write](./write/)(**float**) | Stampa la rappresentazione stringa del valore a virgola mobile a precisione singola sullo stream di output standard. |
| static void [Write](./write/)(**int32_t**) | Stampa la rappresentazione stringa del valore intero a 32 bit sullo stream di output standard. |
| static void [Write](./write/)(**int64_t**) | Stampa la rappresentazione stringa del valore intero a 64 bit sullo stream di output standard. |
| static void [Write](./write/)(const [String](../string/)\&) | Stampa l'oggetto stringa specificato sullo stream di output standard. |
| static void [Write](./write/)(const char_t *) | Stampa la c-string specificata sullo stream di output standard. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Stampa la rappresentazione stringa del valore [TypeInfo](../typeinfo/) sullo stream di output standard. |
| static void [Write](./write/)(**uint32_t**) | Stampa la rappresentazione stringa del valore intero senza segno a 32 bit sullo stream di output standard. |
| static void [Write](./write/)(**uint64_t**) | Stampa la rappresentazione stringa del valore intero senza segno a 64 bit sullo stream di output standard. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Stampa la rappresentazione stringa dell'intervallo specificato dell'array di caratteri specificato sullo stream di output standard. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Stampa la rappresentazione stringa degli argomenti specificati formattati secondo il formato indicato sullo stream di output standard. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Stampa il terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Stampa la rappresentazione stringa dell'oggetto specificato seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(**bool**) | Stampa la rappresentazione stringa del valore bool seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(char_t) | Stampa il valore carattere specificato seguito dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Stampa la rappresentazione stringa dell'array di caratteri specificato seguito dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Stampa la rappresentazione stringa del valore [Decimal](../decimal/) seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(**double**) | Stampa la rappresentazione stringa del valore a virgola mobile a doppia precisione seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(**float**) | Stampa la rappresentazione stringa del valore a virgola mobile a precisione singola seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(**int32_t**) | Stampa la rappresentazione stringa del valore intero a 32 bit seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(**int64_t**) | Stampa la rappresentazione stringa del valore intero a 64 bit seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Stampa l'oggetto stringa specificato seguito dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const char_t *) | Stampa la c-string specificata seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Stampa la rappresentazione stringa del valore [TypeInfo](../typeinfo/) seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Stampa la rappresentazione stringa del valore intero senza segno a 32 bit seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Stampa la rappresentazione stringa del valore intero senza segno a 64 bit seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Stampa la rappresentazione stringa dell'intervallo specificato dell'array di caratteri specificato seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Stampa la rappresentazione stringa dell'oggetto Exception specificato seguito dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Stampa la rappresentazione stringa degli argomenti specificati formattati secondo il formato indicato, seguita dal terminatore di riga corrente sullo stream di output standard. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Osservazioni



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Stampa il messaggio di saluto.
  Console::WriteLine(u"Hello, world!");

  // Crea un'istanza della classe 'std::array'.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Stampa gli elementi dell'array.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
Hello, world!
1 2 3 4 5
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)
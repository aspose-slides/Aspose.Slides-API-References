---
title: Console
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Methoden zum Ausgeben von Daten auf den Standardausgabestream bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 196
url: /de/system/console/
---
## Console Klasse

Stellt Methoden zum Ausgeben von Daten auf den Standardausgabestream bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class Console
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static void [Beep](./beep/)() | NICHT IMPLEMENTIERT. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Gibt einen gemeinsamen Zeiger zurück, der auf das Objekt zeigt, das den Standardfehler-Stream repräsentiert. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Gibt einen gemeinsamen Zeiger zurück, der auf das Objekt zeigt, das den Standard-Eingabestream repräsentiert. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Gibt einen gemeinsamen Zeiger zurück, der auf das Objekt zeigt, das den Standardausgabestream repräsentiert. |
| static void [Mute](./mute/)(**bool**) | Stummschaltet oder hebt die Stummschaltung des Standardausgabestreams auf. |
| static void [ReadKey](./readkey/)() | NICHT IMPLEMENTIERT. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Setzt die Beschriftung des Konsolenfensters. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Weist das angegebene Objekt der Error-Eigenschaft der Klasse zu. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Setzt die In-Eigenschaft auf das angegebene TextReader-Objekt. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Weist das angegebene Objekt der Out-Eigenschaft der Klasse zu. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Gibt die Zeichenkettenrepräsentation des angegebenen Objekts auf dem Standardausgabestream aus. |
| static void [Write](./write/)(**bool**) | Gibt die Zeichenkettenrepräsentation des booleschen Wertes auf dem Standardausgabestream aus. |
| static void [Write](./write/)(char_t) | Gibt den angegebenen Zeichenwert auf dem Standardausgabestream aus. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Gibt die Zeichenkettenrepräsentation des angegebenen Zeichen-Arrays auf dem Standardausgabestream aus. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Gibt die Zeichenkettenrepräsentation des [Decimal](../decimal/)-Wertes auf dem Standardausgabestream aus. |
| static void [Write](./write/)(**double**) | Gibt die Zeichenkettenrepräsentation des double-Präzisions-Gleitkommawerts auf dem Standardausgabestream aus. |
| static void [Write](./write/)(**float**) | Gibt die Zeichenkettenrepräsentation des single-Präzisions-Gleitkommawerts auf dem Standardausgabestream aus. |
| static void [Write](./write/)(**int32_t**) | Gibt die Zeichenkettenrepräsentation des 32-Bit-Integerwerts auf dem Standardausgabestream aus. |
| static void [Write](./write/)(**int64_t**) | Gibt die Zeichenkettenrepräsentation des 64-Bit-Integerwerts auf dem Standardausgabestream aus. |
| static void [Write](./write/)(const [String](../string/)\&) | Gibt das angegebene String-Objekt auf dem Standardausgabestream aus. |
| static void [Write](./write/)(const char_t *) | Gibt die angegebene C-Zeichenkette auf dem Standardausgabestream aus. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Gibt die Zeichenkettenrepräsentation des [TypeInfo](../typeinfo/)-Wertes auf dem Standardausgabestream aus. |
| static void [Write](./write/)(**uint32_t**) | Gibt die Zeichenkettenrepräsentation des vorzeichenlosen 32-Bit-Integerwerts auf dem Standardausgabestream aus. |
| static void [Write](./write/)(**uint64_t**) | Gibt die Zeichenkettenrepräsentation des vorzeichenlosen 64-Bit-Integerwerts auf dem Standardausgabestream aus. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Gibt die Zeichenkettenrepräsentation des angegebenen Bereichs des angegebenen Zeichen-Arrays auf dem Standardausgabestream aus. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Gibt die Zeichenkettenrepräsentation der angegebenen Argumente, formatiert gemäß dem angegebenen Format, auf dem Standardausgabestream aus. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Gibt das aktuelle Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Gibt die Zeichenkettenrepräsentation des angegebenen Objekts gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(**bool**) | Gibt die Zeichenkettenrepräsentation des booleschen Wertes gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(char_t) | Gibt den angegebenen Zeichenwert gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Gibt die Zeichenkettenrepräsentation des angegebenen Zeichen-Arrays gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Gibt die Zeichenkettenrepräsentation des [Decimal](../decimal/)-Wertes gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(**double**) | Gibt die Zeichenkettenrepräsentation des double-Präzisions-Gleitkommawerts gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(**float**) | Gibt die Zeichenkettenrepräsentation des single-Präzisions-Gleitkommawerts gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(**int32_t**) | Gibt die Zeichenkettenrepräsentation des 32-Bit-Integerwerts gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(**int64_t**) | Gibt die Zeichenkettenrepräsentation des 64-Bit-Integerwerts gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Gibt das angegebene String-Objekt gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const char_t *) | Gibt die angegebene C-Zeichenkette gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Gibt die Zeichenkettenrepräsentation des [TypeInfo](../typeinfo/)-Wertes gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Gibt die Zeichenkettenrepräsentation des vorzeichenlosen 32-Bit-Integerwerts gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Gibt die Zeichenkettenrepräsentation des vorzeichenlosen 64-Bit-Integerwerts gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Gibt die Zeichenkettenrepräsentation des angegebenen Bereichs des angegebenen Zeichen-Arrays gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Gibt die Zeichenkettenrepräsentation des angegebenen Exception-Objekts gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Gibt die Zeichenkettenrepräsentation der angegebenen Argumente, formatiert gemäß dem angegebenen Format, gefolgt vom aktuellen Zeilenendezeichen auf dem Standardausgabestream aus. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Anmerkungen



```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Gibt die Begrüßungsnachricht aus.
  Console::WriteLine(u"Hello, world!");

  // Erzeugt eine Instanz der 'std::array'-Klasse.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Gibt die Elemente des Arrays aus.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Hello, world!
1 2 3 4 5
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
---
title: Console
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt methoden voor het uitvoeren van gegevens naar de standaardoutputstroom. Dit is een statisch type zonder instantiediensten. U mag nooit op welke manier dan ook instanties ervan maken.
type: docs
weight: 196
url: /nl/system/console/
---
## Console klasse

Biedt methoden voor het uitvoeren van gegevens naar de standaardoutputstroom. Dit is een statisch type zonder instantiediensten. U dient nooit op welke manier dan ook instanties ervan te maken.

```cpp
class Console
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static void [Beep](./beep/)() | NIET GEREALISEERD. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Error](./get_error/)() | Retourneert een gedeelde pointer die naar het object wijst dat de standaardfoutstroom voorstelt. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\& [get_In](./get_in/)() | Retourneert een gedeelde pointer die naar het object wijst dat de standaardinvoerstroom voorstelt. |
| static [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\& [get_Out](./get_out/)() | Retourneert een gedeelde pointer die naar het object wijst dat de standaardoutputstroom voorstelt. |
| static void [Mute](./mute/)(**bool**) | Zet de demping van de standaardoutputstroom aan of uit. |
| static void [ReadKey](./readkey/)() | NIET GEREALISEERD. |
| static void [set_Title](./set_title/)(const [String](../string/)\&) | Stelt de titel van het consolevenster in. |
| static void [SetError](./seterror/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Wijst het opgegeven object toe aan de Error-eigenschap van de klasse. |
| static void [SetIn](./setin/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextReader](../../system.io/textreader/)\>\&) | Stelt de In-eigenschap in op het opgegeven TextReader-object. |
| static void [SetOut](./setout/)(const [SharedPtr](../sharedptr/)\<[System::IO::TextWriter](../../system.io/textwriter/)\>\&) | Wijst het opgegeven object toe aan de Out-eigenschap van de klasse. |
| static void [Write](./write/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Schrijft de tekenreeksrepresentatie van het opgegeven object naar de standaardoutputstroom. |
| static void [Write](./write/)(**bool**) | Schrijft de tekenreeksrepresentatie van een bool-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(char_t) | Schrijft de opgegeven tekenwaarde naar de standaardoutputstroom. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Schrijft de tekenreeksrepresentatie van de opgegeven tekenreeksarray naar de standaardoutputstroom. |
| static void [Write](./write/)(const [Decimal](../decimal/)\&) | Schrijft de tekenreeksrepresentatie van een [Decimal](../decimal/)-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(**double**) | Schrijft de tekenreeksrepresentatie van een double-precisie floating-point-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(**float**) | Schrijft de tekenreeksrepresentatie van een single-precisie floating-point-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(**int32_t**) | Schrijft de tekenreeksrepresentatie van een 32-bit integer-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(**int64_t**) | Schrijft de tekenreeksrepresentatie van een 64-bit integer-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(const [String](../string/)\&) | Schrijft het opgegeven string-object naar de standaardoutputstroom. |
| static void [Write](./write/)(const char_t *) | Schrijft de opgegeven C-string naar de standaardoutputstroom. |
| static void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) | Schrijft de tekenreeksrepresentatie van een [TypeInfo](../typeinfo/)-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(**uint32_t**) | Schrijft de tekenreeksrepresentatie van een unsigned 32-bit integer-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(**uint64_t**) | Schrijft de tekenreeksrepresentatie van een unsigned 64-bit integer-waarde naar de standaardoutputstroom. |
| static void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Schrijft de tekenreeksrepresentatie van het opgegeven bereik van de opgegeven tekenreeksarray naar de standaardoutputstroom. |
| static void [Write](./write/)(const [String](../string/)\&, Args\&&...) | Schrijft de tekenreeksrepresentatie van de opgegeven argumenten geformatteerd volgens het opgegeven formaat naar de standaardoutputstroom. |
| static void [Write](./write/)(const char *) |  |
| static void [WriteLine](./writeline/)() | Schrijft de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Schrijft de tekenreeksrepresentatie van het opgegeven object gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(**bool**) | Schrijft de tekenreeksrepresentatie van een bool-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(char_t) | Schrijft de opgegeven tekenwaarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) | Schrijft de tekenreeksrepresentatie van de opgegeven tekenreeksarray gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const [Decimal](../decimal/)\&) | Schrijft de tekenreeksrepresentatie van een [Decimal](../decimal/)-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(**double**) | Schrijft de tekenreeksrepresentatie van een double-precisie floating-point-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(**float**) | Schrijft de tekenreeksrepresentatie van een single-precisie floating-point-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(**int32_t**) | Schrijft de tekenreeksrepresentatie van een 32-bit integer-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(**int64_t**) | Schrijft de tekenreeksrepresentatie van een 64-bit integer-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&) | Schrijft het opgegeven string-object gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const char_t *) | Schrijft de opgegeven C-string gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) | Schrijft de tekenreeksrepresentatie van een [TypeInfo](../typeinfo/)-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(**uint32_t**) | Schrijft de tekenreeksrepresentatie van een unsigned 32-bit integer-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(**uint64_t**) | Schrijft de tekenreeksrepresentatie van een unsigned 64-bit integer-waarde gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) | Schrijft de tekenreeksrepresentatie van het opgegeven bereik van de opgegeven tekenreeksarray gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const [Exception](../exception/)\&) | Schrijft de tekenreeksrepresentatie van het opgegeven Exception-object gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const [String](../string/)\&, Args\&&...) | Schrijft de tekenreeksrepresentatie van de opgegeven argumenten geformatteerd volgens het opgegeven formaat gevolgd door de huidige regeleindetekens naar de standaardoutputstroom. |
| static void [WriteLine](./writeline/)(const char *) |  |

## Opmerkingen

```cpp
#include "system/console.h"
#include <array>

int main()
{
  using namespace System;

  // Print het hello-bericht.
  Console::WriteLine(u"Hello, world!");

  // Maak een instantie van de 'std::array' klasse.
  std::array<int, 5> arr = {1, 2, 3, 4, 5};

  // Print elementen van de array.
  for (auto el: arr)
  {
    Console::Write(u"{0} ", el);
  }
  Console::WriteLine();

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
Hello, world!
1 2 3 4 5
*/
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)
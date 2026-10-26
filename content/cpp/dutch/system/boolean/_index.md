---
title: Boolean
second_title: Aspose.Slides voor C++ API-referentie
description: Klasse die statische leden van System.Boolean .Net type bevat.
type: docs
weight: 79
url: /nl/system/boolean/
---
## Boolean klasse


Klasse die statische leden van [System.Boolean](./) .[Net](../../system.net/) type bevat.

```cpp
class Boolean
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven string naar een waarde van bool-type. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Converteert de opgegeven string naar een waarde van bool-type. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) representatie van de booleaanse waarde 'false'. |
| static [TrueString](./truestring/) | [String](../string/) representatie van de booleaanse waarde 'true'. |
## Opmerkingen



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Maak de booleanvariabele aan.
  bool isWeekend = false;

  // Parse de invoerstring en druk het resultaat af.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
Is weekend: Ja
*/
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)
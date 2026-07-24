---
title: Boolean
second_title: Aspose.Slides für C++ API-Referenz
description: Klasse, die statische Mitglieder des System.Boolean .Net Typs enthält.
type: docs
weight: 79
url: /de/system/boolean/
---
## Boolean Klasse

Klasse, die statische Mitglieder des Typs [System.Boolean](./) .[Net](../../system.net/) enthält.

```cpp
class Boolean
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkette in einen Wert des Typs bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Konvertiert die angegebene Zeichenkette in einen Wert des Typs bool. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) Darstellung des booleschen Werts 'false'. |
| static [TrueString](./truestring/) | [String](../string/) Darstellung des booleschen Werts 'true'. |

## Hinweise

```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Erstelle die boolesche Variable.
  bool isWeekend = false;

  // Parse die Eingabezeichenkette und gib das Ergebnis aus.
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
Dieses Codebeispiel erzeugt die folgende Ausgabe:
Is weekend: Yes
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)
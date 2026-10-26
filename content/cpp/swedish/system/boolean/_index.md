---
title: Boolean
second_title: Aspose.Slides för C++ API-referens
description: Klass som innehåller statiska medlemmar av System.Boolean .Net-typen.
type: docs
weight: 79
url: /sv/system/boolean/
---
## Boolean klass

Klass som innehåller statiska medlemmar av [System.Boolean](./) .[Net](../../system.net/) typ.

```cpp
class Boolean
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Konverterar den angivna strängen till ett värde av typen bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Konverterar den angivna strängen till ett värde av typen bool. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) representation av det booleska värdet 'false'. |
| static [TrueString](./truestring/) | [String](../string/) representation av det booleska värdet 'true'. |
## Anmärkningar



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Skapa den boolska variabeln.
  bool isWeekend = false;

  // Analysera inmatningssträngen och skriv ut resultatet.
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
Detta kodexempel producerar följande utdata:
Är helg: Ja
*/
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)
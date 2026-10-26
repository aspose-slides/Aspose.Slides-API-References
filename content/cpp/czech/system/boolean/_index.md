---
title: Boolean
second_title: Referenční příručka API Aspose.Slides pro C++
description: Třída, která uchovává statické členy typu System.Boolean .Net.
type: docs
weight: 79
url: /cs/system/boolean/
---
## Třída Boolean


Třída, která uchovává statické členy typu [System.Boolean](./) .[Net](../../system.net/).

```cpp
class Boolean
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Převádí zadaný řetězec na hodnotu typu bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Převádí zadaný řetězec na hodnotu typu bool. |
## Pole

| Pole | Popis |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) reprezentace logické hodnoty 'false'. |
| static [TrueString](./truestring/) | [String](../string/) reprezentace logické hodnoty 'true'. |
## Poznámky



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Vytvořte bool proměnnou.
  bool isWeekend = false;

  // Parsujte vstupní řetězec a vytiskněte výsledek.
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
Tento ukázkový kód produkuje následující výstup:
Je víkend: Ano
*/
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)
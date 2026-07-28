---
title: Boolean
second_title: Aspose.Slides dla C++ - Referencja API
description: Klasa przechowująca statyczne elementy typu System.Boolean .Net.
type: docs
weight: 79
url: /pl/system/boolean/
---
## Boolean klasa

Klasa, która przechowuje statyczne elementy typu [System.Boolean](./) .[Net](../../system.net/).

```cpp
class Boolean
```

## Metody

| Metoda | Opis |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Konwertuje podany ciąg znaków na wartość typu bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Konwertuje podany ciąg znaków na wartość typu bool. |

## Pola

| Pole | Opis |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) reprezentacja wartości logicznej 'false'. |
| static [TrueString](./truestring/) | [String](../string/) reprezentacja wartości logicznej 'true'. |

## Uwagi



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Utwórz zmienną logiczną.
  bool isWeekend = false;

  // Parsuj łańcuch wejściowy i wyświetl wynik.
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
Ten przykład kodu generuje następujący wynik:
Czy weekend: Tak
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)
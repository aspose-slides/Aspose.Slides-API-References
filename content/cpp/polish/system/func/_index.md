---
title: Func
second_title: Odwołanie API Aspose.Slides dla C++
description: "Obiekt delegata funkcji. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 859
url: /pl/system/func/
---
## Func klasa

Function delegate. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### Parametry szablonu

| Parameter | Description |
| --- | --- |
| Args | Argumenty wywołania, a następnie obowiązkowy typ zwracany. |

## Metody

| Method | Description |
| --- | --- |
|  [Func](./func/)() | Domyślny konstruktor, który tworzy null-Func. |
|  [Func](./func/)(T\&&) | Konstruktor, który tworzy obiekt [Func](./) i przypisuje mu wartość (czy to rzeczywiste wywołanie zwrotne, czy nullptr). |
|  [Func](./func/)(const [Func](./)\&) | Konstruktor kopiujący. |
|  [Func](./func/)([Func](./)\&&) | Konstruktor przenoszący. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Przypisanie kopiujące. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Przypisanie przenoszące. |
|  [~Func](./~func/)() | Destruktor. |

## Uwagi

```cpp
#include "system/func.h"
#include <iostream"

// Ta funkcja przyjmuje jako parametr instancję delegata System::Func.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Utwórz instancję delegata System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Przekaż utworzoną instancję jako argument funkcji.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Ten przykład kodu generuje następujący wynik:
1
4
9
*/
```

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)
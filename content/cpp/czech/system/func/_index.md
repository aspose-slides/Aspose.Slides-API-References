---
title: Func
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Delegát funkce. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 859
url: /cs/system/func/
---
## Func třída


Delegát funkce. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) k řízení objektů tohoto typu.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| Args | Argumenty volání, následně povinný návratový typ. |
## Metody

| Metoda | Popis |
| --- | --- |
|  [Func](./func/)() | Výchozí konstruktor, který vytvoří null-Func. |
|  [Func](./func/)(T\&&) | Konstruktor, který vytvoří objekt [Func](./) a přiřadí mu hodnotu (buď skutečné zpětné volání, nebo nullptr). |
|  [Func](./func/)(const [Func](./)\&) | Kopírovací konstruktor. |
|  [Func](./func/)([Func](./)\&&) | Konstruktor přesunu. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Operátor přiřazení kopie. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Operátor přiřazení přesunu. |
|  [~Func](./~func/)() | Destruktor. |
## Poznámky



```cpp
#include "system/func.h"
#include <iostream"

// Tato funkce přijímá jako parametr instanci delegáta System::Func.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Vytvořte instanci delegáta System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Předejte vytvořenou instanci jako argument funkce.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Tento ukázkový kód produkuje následující výstup:
1
4
9
*/
```

## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)
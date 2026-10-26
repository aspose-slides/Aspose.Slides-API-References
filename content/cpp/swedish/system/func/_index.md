---
title: Func
second_title: Aspose.Slides för C++ API-referens
description: "Funktionsdelegat. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller som referens. Använd aldrig System::SmartPtr-klass för att hantera objekt av denna typ."
type: docs
weight: 859
url: /sv/system/func/
---
## Func klass


Funktionsdelegat. Denna typ bör allokeras på stacken och överföras till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Args | Anropsargument, sedan obligatorisk returtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [Func](./func/)() | Standardkonstruktor som skapar null-Func. |
|  [Func](./func/)(T\&&) | Konstruktor som konstruerar [Func](./)-objekt och tilldelar värde (antingen faktisk återuppringning eller nullptr) till det. |
|  [Func](./func/)(const [Func](./)\&) | Kopieringskonstruktor. |
|  [Func](./func/)([Func](./)\&&) | Flyttkonstruktor. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Kopieringsoperator. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Flyttoperator. |
|  [~Func](./~func/)() | Destruktor. |
## Anmärkningar



```cpp
#include "system/func.h"
#include <iostream"

// Den här funktionen tar emot en instans av delegaten System::Func som en parameter.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Skapa en instans av delegaten System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Skicka den skapade instansen som ett funktionsargument.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Det här kodexemplet ger följande utskrift:
1
4
9
*/
```

## Se även

* namnrymd [System](../)
* bibliotek [Aspose.Slides](../../)
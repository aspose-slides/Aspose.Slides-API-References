---
title: Func
second_title: Aspose.Slides voor C++ API-referentie
description: "Functie-delegaat. Dit type moet op de stack worden toegewezen en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr-klasse om objecten van dit type te beheren."
type: docs
weight: 859
url: /nl/system/func/
---
## Func klasse


Functie-delegate. Dit type moet op de stack worden toegewezen en aan functies door waarde of door referentie worden doorgegeven. Gebruik nooit [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| Args | Aanroepargumenten, gevolgd door het verplichte retourtype. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [Func](./func/)() | Standaardconstructor die null-Func maakt. |
|  [Func](./func/)(T\&&) | Constructor die een [Func](./) object maakt en er een waarde (ofwel echte callback of nullptr) aan toewijst. |
|  [Func](./func/)(const [Func](./)\&) | Kopieconstructor. |
|  [Func](./func/)([Func](./)\&&) | Verplaatsingsconstructor. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Kopietoewijzing. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Verplaatsingstoewijzing. |
|  [~Func](./~func/)() | Destruktor. |
## Opmerkingen



```cpp
#include "system/func.h"
#include <iostream"

// Deze functie accepteert een instantie van de System::Func delegate als parameter.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Maak een instantie van de System::Func delegate aan.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Geef de gemaakte instantie door als functie-argument.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
1
4
9
*/
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)
---
title: Func
second_title: Riferimento API Aspose.Slides per C++
description: "Delegate di funzione. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non usare mai la classe System::SmartPtr per gestire gli oggetti di questo tipo."
type: docs
weight: 859
url: /it/system/func/
---
## Func classe


Delegate di funzione. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non usare mai la classe [System::SmartPtr](../smartptr/) per gestire gli oggetti di questo tipo.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Args | Argomenti della chiamata, poi tipo di ritorno obbligatorio. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [Func](./func/)() | Costruttore predefinito che crea null-Func. |
|  [Func](./func/)(T\&&) | Costruttore che crea l'oggetto [Func](./) e assegna ad esso il valore (sia callback reale sia nullptr). |
|  [Func](./func/)(const [Func](./)\&) | Costruttore di copia. |
|  [Func](./func/)([Func](./)\&&) | Costruttore di spostamento. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Operatore di assegnazione per copia. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Operatore di assegnazione per spostamento. |
|  [~Func](./~func/)() | Distruttore. |
## Osservazioni



```cpp
#include "system/func.h"
#include <iostream"

// Questa funzione accetta un'istanza del delegato System::Func come parametro.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Crea un'istanza del delegato System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Passa l'istanza creata come argomento della funzione.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
1
4
9
*/
```

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)
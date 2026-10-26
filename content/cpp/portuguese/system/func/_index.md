---
title: Func
second_title: Aspose.Slides para Referência da API C++
description: "Delegate de função. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 859
url: /pt/system/func/
---
## Func classe

Delegate de função. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos desse tipo.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Args | Argumentos da chamada, depois o tipo de retorno obrigatório. |

## Métodos

| Método | Descrição |
| --- | --- |
|  [Func](./func/)() | Construtor padrão que cria um null-Func. |
|  [Func](./func/)(T\&&) | Construtor que cria um objeto [Func](./) e atribui a ele um valor (ou o callback real ou nullptr). |
|  [Func](./func/)(const [Func](./)\&) | Construtor de cópia. |
|  [Func](./func/)([Func](./)\&&) | Construtor de movimentação. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Atribuição de cópia. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Atribuição de movimentação. |
|  [~Func](./~func/)() | Destrutor. |

## Observações

```cpp
#include "system/func.h"
#include <iostream>

// Esta função aceita uma instância do delegate System::Func como parâmetro.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Cria uma instância do delegate System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Passa a instância criada como argumento da função.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Este exemplo de código produz a saída a seguir:
1
4
9
*/
```

## Ver também

* namespace [System](../)
* Biblioteca [Aspose.Slides](../../)
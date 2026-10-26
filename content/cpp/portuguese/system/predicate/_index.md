---
title: Predicate
second_title: Referência da API Aspose.Slides para C++
description: Representa um ponteiro para um predicado - uma entidade invocável que aceita um único argumento e retorna um valor bool.
type: docs
weight: 4187
url: /pt/system/predicate/
---
## typedef de Predicado


Representa um ponteiro para um predicado - uma entidade invocável que aceita um único argumento e retorna um valor bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Observações



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Preencha o array.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Crie o predicado que retorna um elemento do array maior que 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Encontre o primeiro elemento do array usando o predicado criado e imprima-o.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
5
*/
```

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)
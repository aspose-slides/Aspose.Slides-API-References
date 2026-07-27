---
title: Action
second_title: Referência da API Aspose.Slides para C++
description: Tipo de delegado que faz referência a métodos que não retornam nenhum valor.
type: docs
weight: 3602
url: /pt/system/action/
---
## Typedef de ação

Tipo de delegado que faz referência a métodos que não retornam nenhum valor.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Observações

```cpp
#include <system/action.h>

using namespace System;

// A função que imprime a string passada.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Cria uma instância de Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Chama a ação.
  action(u"Hello, world!");

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
Olá, mundo!
*/
```

## Ver também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)
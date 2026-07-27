---
title: Action
second_title: Aspose.Slides para C++ API Referencia
description: Tipo de delegado que hace referencia a métodos que no devuelven un valor.
type: docs
weight: 3602
url: /es/system/action/
---
## Action typedef


Tipo de delegado que hace referencia a métodos que no devuelven un valor.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Observaciones



```cpp
#include <system/action.h>

using namespace System;

// La función que imprime la cadena pasada.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Crear una instancia de Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Llamar a la acción.
  action(u"Hello, world!");

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
Hello, world!
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
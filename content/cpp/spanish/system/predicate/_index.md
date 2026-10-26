---
title: Predicate
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un puntero a un predicado - una entidad invocable que acepta un único argumento y devuelve un valor bool.
type: docs
weight: 4187
url: /es/system/predicate/
---
## typedef de predicado


Representa un puntero a un predicado - una entidad invocable que acepta un único argumento y devuelve un valor bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Observaciones



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Llenar el arreglo.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Crear el predicado que devuelve un elemento del arreglo que es mayor que 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Encontrar el primer elemento del arreglo usando el predicado creado y mostrarlo.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
5
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
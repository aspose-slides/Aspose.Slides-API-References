---
title: Boolean
second_title: Referencia de API de Aspose.Slides para C++
description: Clase que mantiene los miembros estáticos del tipo System.Boolean .Net.
type: docs
weight: 79
url: /es/system/boolean/
---
## Clase Boolean


Clase que mantiene los miembros estáticos de [System.Boolean](./) .[Net](../../system.net/) tipo.

```cpp
class Boolean
```

## Métodos

| Método | Descripción |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Convierte la cadena especificada a un valor del tipo bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Convierte la cadena especificada a un valor del tipo bool. |

## Campos

| Campo | Descripción |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) representación del valor booleano 'false'. |
| static [TrueString](./truestring/) | [String](../string/) representación del valor booleano 'true'. |

## Observaciones



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Crear la variable booleana.
  bool isWeekend = false;

  // Analizar la cadena de entrada e imprimir el resultado.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
Este ejemplo de código produce la siguiente salida:
Fin de semana: Sí
*/
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)
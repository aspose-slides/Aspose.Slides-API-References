---
title: Boolean
second_title: Aspose.Slides para C++ Referência da API
description: Classe que mantém membros estáticos do tipo System.Boolean .Net.
type: docs
weight: 79
url: /pt/system/boolean/
---
## Classe Boolean

Classe que mantém membros estáticos do tipo [System.Boolean](./) .[Net](../../system.net/).

```cpp
class Boolean
```

## Métodos

| Método | Descrição |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Converte a string especificada para um valor do tipo bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Converte a string especificada para um valor do tipo bool. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) representação do valor booleano 'false'. |
| static [TrueString](./truestring/) | [String](../string/) representação do valor booleano 'true'. |

## Observações

```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Cria a variável boolean.
  bool isWeekend = false;

  // Analisa a string de entrada e imprime o resultado.
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
Este exemplo de código produz a seguinte saída:
Is weekend: Yes
*/
```

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)
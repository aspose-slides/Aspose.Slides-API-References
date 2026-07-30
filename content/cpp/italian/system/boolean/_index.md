---
title: Boolean
second_title: Riferimento API di Aspose.Slides per C++
description: Classe che conserva i membri statici del tipo System.Boolean .Net.
type: docs
weight: 79
url: /it/system/boolean/
---
## Classe Boolean

Classe che conserva i membri statici del tipo [System.Boolean](./) .[Net](../../system.net/).

```cpp
class Boolean
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Converte la stringa specificata in un valore di tipo bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Converte la stringa specificata in un valore di tipo bool. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) rappresentazione del valore booleano 'false'. |
| static [TrueString](./truestring/) | [String](../string/) rappresentazione del valore booleano 'true'. |

## Osservazioni

```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Crea la variabile booleana.
  bool isWeekend = false;

  // Analizza la stringa di input e stampa il risultato.
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
Questo esempio di codice produce il seguente output:
È weekend: Sì
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)
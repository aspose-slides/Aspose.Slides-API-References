---
title: SafeInvoke()
second_title: Referência da API Aspose.Slides para C++
description: Implementação da tradução do operador '?.'.
type: docs
weight: 2653
url: /pt/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) função


Implementação da tradução do operador '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T0 | tipo da expressão. |
| T1 | Tipo do lambda que encapsula a expressão 'WhenTrue'. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expr | T0\&& | valor da expressão. |
| func | T1\&& | expressão 'WhenTrue' vinculada ao functor. |

### Valor de retorno

Se o valor de expr não for nulo, retorna func chamado com seu valor como primeiro argumento; caso contrário, retorna nulo.

## Veja Também

* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)
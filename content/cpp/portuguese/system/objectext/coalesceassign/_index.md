---
title: CoalesceAssign()
second_title: Referência da API Aspose.Slides para C++
description: Implementação da tradução do operador '??='.
type: docs
weight: 183
url: /pt/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) método

Implementação da tradução do operador '??='.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T0 | Tipo do valor LHS. |
| T1 | Tipo do lambda que encapsula a expressão RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T0\& | Valor LHS. |
| func | T1 | Expressão RHS. |

### Valor de retorno

Se o valor LHS não for nulo, retorna LHS; caso contrário, calcula a expressão RHS e retorna o resultado.

## Veja Também

* Classe [ObjectExt](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)
---
title: CoalesceInternal()
second_title: Aspose.Slides para Referência da API C++
description: Implementação da tradução do operador '??' para tipos não anuláveis. Sobrecarga para o caso em que RT2 é convertível para RT1.
type: docs
weight: 157
url: /pt/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) método

Implementação da tradução do operador '??' para tipos não anuláveis. Sobrecarga para o caso em que RT2 é convertível para RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T0 | Tipo de valor LHS. |
| T1 | Tipo de lambda que encapsula a expressão RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | RT1 | Valor LHS. |
| func | F | Expressão RHS. |

### Valor de Retorno

Se o valor LHS não for nulo, retorna LHS; caso contrário, calcula a expressão RHS e retorna o resultado.

## Veja Também

* Classe [ObjectExt](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)
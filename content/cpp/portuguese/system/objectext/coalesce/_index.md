---
title: Coalesce()
second_title: Referência da API Aspose.Slides para C++
description: Implementação da tradução do operador '??' para tipos não anuláveis.
type: docs
weight: 170
url: /pt/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) método

Implementação da tradução do operador '??' para tipos não anuláveis.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T0 | tipo de valor LHS. |
| T1 | Tipo da lambda que encapsula a expressão RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | T0 | valor LHS. |
| func | T1 | expressão RHS. |

### Valor de Retorno

Se o valor LHS não for nulo, retorna LHS; caso contrário, calcula a expressão RHS e retorna o resultado.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) método

Implementação da tradução do operador '??' para tipos anuláveis.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T0 | tipo de valor LHS. |
| T1 | Tipo da lambda que encapsula a expressão RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | valor LHS. |
| func | T1 | expressão RHS. |

### Valor de Retorno

Se o valor LHS não for nulo, retorna LHS; caso contrário, calcula a expressão RHS e retorna o resultado.

## Veja Também

* Classe [ObjectExt](../)
* Classe [Nullable](../../nullable/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)
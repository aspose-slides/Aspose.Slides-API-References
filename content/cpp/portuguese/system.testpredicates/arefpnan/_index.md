---
title: AreFPNaN()
second_title: Referência da API Aspose.Slides para C++
description: namespace Details
type: docs
weight: 1
url: /pt/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) function


namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Parâmetros de Template

| Parâmetro | Descrição |
| --- | --- |
| T1 | Primeiro tipo de ponto flutuante. |
| T2 | Segundo tipo de ponto flutuante. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs | T1 | Primeiro valor de ponto flutuante. |
| rhs | T2 | Segundo valor de ponto flutuante. |

### Valor de Retorno

Verdadeiro se tanto **lhs** quanto **rhs** forem valores de ponto flutuante, falso caso contrário.
## Observações


Verifica se dois valores de ponto flutuante são ambos NaNs. Trata a situação quando NaN não sinalizador é suportado. 
## System::TestPredicates::AreFPNaN(T1, T2) function


Verifica se dois valores de ponto flutuante são ambos NaNs. Trata a situação quando NaN não sinalizador não é suportado.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Parâmetros de Template

| Parâmetro | Descrição |
| --- | --- |
| T1 | Primeiro tipo de ponto flutuante. |
| T2 | Segundo tipo de ponto flutuante. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs | T1 | Primeiro valor de ponto flutuante. |
| rhs | T2 | Segundo valor de ponto flutuante. |

### Valor de Retorno

Sempre retorna falso, pois o valor NaN não é suportado.

## Veja Também

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
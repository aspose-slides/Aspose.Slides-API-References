---
title: EqFailure()
second_title: Referência da API Aspose.Slides para C++
description: Formata falha de asserção == para a saída.
type: docs
weight: 27
url: /pt/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) função


Formata falha de asserção == para a saída.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de valor LHS. |
| T2 | Tipo de valor RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T1\& | Valor LHS. |
| rhs | T2\& | Valor RHS. |

### Valor de Retorno

[Object](../../system/object/) envolvendo texto de falha.

## Veja Também

* Espaço de nomes [System::TestPredicates::Details](../)
* Biblioteca [Aspose.Slides](../../)
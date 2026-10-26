---
title: SameFailure()
second_title: Aspose.Slides para C++ Referência da API
description: Formata falha de asserção 'same' para saída.
type: docs
weight: 53
url: /pt/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) função

Formata falha de asserção 'same' para saída.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de valor do LHS. |
| T2 | Tipo de valor do RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T1\& | Valor LHS. |
| rhs | T2\& | Valor RHS. |

### Valor de Retorno

[Object](../../system/object/) envolvendo texto de falha.

## Ver também

* Namespace [System::TestPredicates::Details](../)
* Biblioteca [Aspose.Slides](../../)
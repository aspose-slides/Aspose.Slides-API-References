---
title: NotSameFailure()
second_title: Referência da API Aspose.Slides para C++
description: Formata a falha de asserção 'not same' para a saída.
type: docs
weight: 66
url: /pt/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) função

Formata a falha de asserção 'not same' para saída.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do valor LHS. |
| T2 | Tipo do valor RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T1\& | Valor LHS. |
| rhs | T2\& | Valor RHS. |

### Valor de retorno

[Object](../../system/object/) envolvendo texto de falha.

## Veja Também

* Espaço de nomes [System::TestPredicates::Details](../)
* Biblioteca [Aspose.Slides](../../)
---
title: AreEqual()
second_title: Aspose.Slides para C++ Referência da API
description: Compara por igualdade os argumentos para a tradução da asserção AreEqual.
type: docs
weight: 14
url: /pt/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) função

Compara por igualdade os argumentos para a tradução da asserção AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | tipo de objeto LHS. |
| T2 | tipo de objeto RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | expressão LHS. |
| rhs_expr | const char * | expressão RHS. |
| lhs | T1\&& | valor LHS. |
| rhs | T2\&& | valor RHS. |

### Valor de retorno

resultado da asserção no estilo gtest.

## Veja também

* Namespace [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
---
title: AreNotEqual()
second_title: Referência da API Aspose.Slides para C++
description: Compara argumentos de não-igualdade para a tradução da asserção AreEqual.
type: docs
weight: 40
url: /pt/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) function

Compara argumentos de não-igualdade para a asserção AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo de objeto LHS. |
| T2 | Tipo de objeto RHS. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | Expressão LHS. |
| rhs_expr | const char * | Expressão RHS. |
| lhs | T1\&& | Valor LHS. |
| rhs | T2\&& | Valor RHS. |

### Valor de retorno

Resultado da asserção no estilo gtest.

## Veja também

* Espaço de nomes [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
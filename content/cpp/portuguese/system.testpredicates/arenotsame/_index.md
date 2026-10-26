---
title: AreNotSame()
second_title: Referência da API Aspose.Slides para C++
description: Are-not-same-compara os argumentos para a tradução da asserção AreSame.
type: docs
weight: 92
url: /pt/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) função

Are-not-same-compara argumentos para a tradução da asserção AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |

### Valor de retorno

Resultado da asserção no estilo gtest.

## Veja também

* Espaço de nomes [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
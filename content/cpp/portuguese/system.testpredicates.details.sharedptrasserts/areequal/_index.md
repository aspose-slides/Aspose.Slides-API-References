---
title: AreEqual()
second_title: Referência da API Aspose.Slides for C++
description: Compara a igualdade dos argumentos para a asserção AreEqual.
type: docs
weight: 92
url: /pt/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1\&, const T2\&) function

Compara a igualdade dos argumentos para a asserção AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS tipo de objeto. |
| T2 | RHS tipo de objeto. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expressão. |
| rhs_expr | const char * | RHS expressão. |
| lhs | const T1\& | LHS valor. |
| rhs | const T2\& | RHS valor. |

### Valor de retorno

resultado de asserção no estilo gtest.

## Veja também

* Espaço de nomes [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteca [Aspose.Slides](../../)
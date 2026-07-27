---
title: AreNotEqual()
second_title: Referência da API Aspose.Slides para C++
description: Compara argumentos de desigualdade para a asserção AreNotEqual.
type: docs
weight: 131
url: /pt/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) function


Compara argumentos de desigualdade para a asserção AreNotEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

### Valor de Retorno

gtest-styled assertion result.

## Veja Também

* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteca [Aspose.Slides](../../)
---
title: AreNotEqual()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara por desigualdad los argumentos para la aserción AreNotEqual.
type: docs
weight: 131
url: /es/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) función

Compara por desigualdad los argumentos para la aserción AreNotEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### Valor devuelto

gtest-styled assertion result.

## Ver también

* Espacio de nombres [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteca [Aspose.Slides](../../)
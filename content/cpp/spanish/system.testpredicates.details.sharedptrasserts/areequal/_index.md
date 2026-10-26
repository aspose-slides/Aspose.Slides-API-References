---
title: AreEqual()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara por igualdad los argumentos para la aserción AreEqual.
type: docs
weight: 92
url: /es/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1\&, const T2\&) función

Compara por igualdad los argumentos para la aserción AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo de objeto LHS. |
| T2 | Tipo de objeto RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |

### Valor de retorno

Resultado de aserción con estilo gtest.

## Ver también

* Espacio de nombres [System::TestPredicates::Details::SharedPtrAsserts](../)
* Biblioteca [Aspose.Slides](../../)
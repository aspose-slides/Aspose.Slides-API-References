---
title: NotSameFailure()
second_title: Referencia de API de Aspose.Slides para C++
description: Formatea la falla de aserción 'not same' para la salida.
type: docs
weight: 66
url: /es/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) función

Formatea la falla de aserción 'not same' para la salida.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo de valor LHS. |
| T2 | Tipo de valor RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | T1\& | Valor LHS. |
| rhs | T2\& | Valor RHS. |

### Valor devuelto

[Object](../../system/object/) envolviendo el texto de falla.

## Ver también

* Espacio de nombres [System::TestPredicates::Details](../)
* Biblioteca [Aspose.Slides](../../)
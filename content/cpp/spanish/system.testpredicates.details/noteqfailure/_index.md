---
title: NotEqFailure()
second_title: Referencia de API de Aspose.Slides para C++
description: Formatea el fallo de aserción != para la salida.
type: docs
weight: 40
url: /es/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) function

Formatea el fallo de aserción != para la salida.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo de valor del LHS. |
| T2 | Tipo de valor del RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión del LHS. |
| rhs_expr | const char * | Expresión del RHS. |
| lhs | T1\& | Valor LHS. |
| rhs | T2\& | Valor RHS. |

### Valor de retorno

[Object](../../system/object/) envolviendo el texto del fallo.

## Ver también

* Espacio de nombres [System::TestPredicates::Details](../)
* Biblioteca [Aspose.Slides](../../)
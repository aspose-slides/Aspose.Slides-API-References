---
title: AreNotSame()
second_title: Referencia de API de Aspose.Slides para C++
description: Are-not-same-compares compara los argumentos para la traducción de la aserción AreSame.
type: docs
weight: 92
url: /es/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) función

Are-not-same-compares compara los argumentos para la aserción AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

Resultado de la aserción con estilo gtest.

## Véase también

* Espacio de nombres [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
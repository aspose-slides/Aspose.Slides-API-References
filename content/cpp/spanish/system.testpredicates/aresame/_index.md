---
title: AreSame()
second_title: Referencia de API de Aspose.Slides para C++
description: Are-same-compara argumentos para la traducción de la aserción AreSame.
type: docs
weight: 66
url: /es/system.testpredicates/aresame/
---
## System::TestPredicates::AreSame(const char *, const char *, const T1\&, const T2\&) función

Are-same-compares argumentos para la traducción de la aserción AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo de objeto del LHS. |
| T2 | Tipo de objeto del RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |

### Valor de retorno

Resultado de aserción estilo gtest.

## Ver también

* Espacio de nombres [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
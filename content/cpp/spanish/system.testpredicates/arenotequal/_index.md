---
title: AreNotEqual()
second_title: Referencia de API de Aspose.Slides para C++
description: Compara con desigualdad los argumentos para la traducción de la aserción AreEqual.
type: docs
weight: 40
url: /es/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) función

Compara con desigualdad los argumentos para la traducción de la aserción AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1\&& | Valor LHS. |
| rhs | T2\&& | Valor RHS. |

### Valor de retorno

Resultado de aserción con estilo gtest.

## Ver también

* Espacio de nombres [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
---
title: IsInstanceOf()
second_title: Aspose.Slides para la referencia de API de C++
description: Is-instance-of compara los argumentos para la traducción de la aserción IsInstanceOf.
type: docs
weight: 118
url: /es/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) función


Is-instance-of compara argumentos para la traducción de la aserción IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo de argumento. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Un objeto typeInfo que representa un tipo contra el cual se debe comparar el tipo de **obj** |
| obj | const T\& | Un objeto cuyo tipo comparar con el tipo especificado |

### Valor devuelto

Resultado de aserción con estilo gtest.

## Véase también

* Clase [TypeInfo](../../system/typeinfo/)
* Espacio de nombres [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
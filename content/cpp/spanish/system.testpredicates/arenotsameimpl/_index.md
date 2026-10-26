---
title: AreNotSameImpl()
second_title: Referencia de API de Aspose.Slides para C++
description: Are-not-same compara punteros inteligentes.
type: docs
weight: 105
url: /es/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) función

Are-not-same compara punteros inteligentes.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) función

Are-not-same compara valores que no son punteros.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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

* Estructura [IsSmartPtr](../../system/issmartptr/)
* Espacio de nombres [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
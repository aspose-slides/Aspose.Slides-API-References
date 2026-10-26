---
title: AreSameImpl()
second_title: Referencia de la API de Aspose.Slides para C++
description: Are-same-compara punteros inteligentes.
type: docs
weight: 79
url: /es/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) función


Are-same-compara punteros inteligentes.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

resultado de aserción estilo gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) función


Are-same-compara excepciones.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

resultado de aserción estilo gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) función


Are-same-compara valores que no son punteros.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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

### Valor de retorno

resultado de aserción estilo gtest.

## Ver también

* Estructura [IsSmartPtr](../../system/issmartptr/)
* Estructura [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Espacio de nombres [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
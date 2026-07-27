---
title: AreNotEqualImpl()
second_title: Referencia de la API de Aspose.Slides para C++
description: No-igual compara valores con uno o ambos siendo Decimal.
type: docs
weight: 53
url: /es/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) función


No-igual compara valores con uno o ambos siendo [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) función


No-igual compara tipos no punteros usando el método Equals proporcionado.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) función


No-igual compara tipos no punteros usando el método Equals proporcionado.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) función


No-igual compara tipos no punteros usando el operador != proporcionado.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) función


No-igual compara tipos encapsulables con valores [SmartPtr](../../system/smartptr/) usando desempaquetado.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | T | Valor LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) función


No-igual compara tipos encapsulables con valores [SmartPtr](../../system/smartptr/) usando desempaquetado.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor LHS. |
| rhs | T | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) función


No-igual compara tipo aleatorio con nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | T | Valor LHS. |
| s | std::nullptr_t | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) función


No-igual compara tipo aleatorio con nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| rhs | std::nullptr_t | Valor RHS. |
| s | T | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) función


Igual compara tipos puntero.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo LHS. |
| T2 | Tipo RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const T1\& | Valor LHS. |
| rhs | const T2\& | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor devuelto

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) función


Igual compara tipos aleatorios usando algoritmos gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo LHS. |
| T2 | Tipo RHS. |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | T1 | Valor LHS. |
| rhs | T2 | Valor RHS. |

### Valor devuelto

Resultado de aserción con estilo gtest.

## Ver también

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Clase [Object](../../system/object/)
* Estructura [IsSmartPtr](../../system/issmartptr/)
* Estructura [IsBoxable](../../system/isboxable/)
* Espacio de nombres [System::TestPredicates](../)
* Biblioteca [Aspose.Slides](../../)
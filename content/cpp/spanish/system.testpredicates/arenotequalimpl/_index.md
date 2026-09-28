---
title: AreNotEqualImpl()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara para desigualdad valores, uno o ambos siendo Decimal.
type: docs
weight: 53
url: /es/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) función

Compara para desigualdad valores, uno o ambos siendo [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T1 | Tipo del objeto LHS. |
| T2 | Tipo del objeto RHS. |

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

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) función

Compara para desigualdad dos valores [System::String](../../system/string/), protegiendo contra la invocación de una función miembro en un [String](../../system/string/) nulo. Plantillado por las mismas razones de exclusión basadas en deducción que la sobrecarga AreEqualImpl [String](../../system/string/) anterior.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/), restringido a [System::String](../../system/string/). |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const T\& | Valor LHS. |
| rhs | const T\& | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) función

Compara para desigualdad tipos no puntero usando el método Equals proporcionado.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) función

Compara para desigualdad tipos no puntero usando el método Equals proporcionado.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
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

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) función

Compara para desigualdad tipos no puntero usando el operador != proporcionado.

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

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) función

Compara para desigualdad valores [SmartPtr](../../system/smartptr/) empaquetables usando unboxing.

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

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) función

Compara para desigualdad valores [SmartPtr](../../system/smartptr/) empaquetables usando unboxing.

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

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) función

Compara para desigualdad tipo aleatorio con nullptr.

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

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) función

Compara para desigualdad tipo aleatorio con nullptr.

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

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) función

Compara para igualdad tipos puntero.

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

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) función

Compara para igualdad tipos aleatorio usando algoritmos gtest.

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

### Valor de retorno

Resultado de aserción con estilo gtest.

## Ver también

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
---
title: AreEqualImpl()
second_title: Referencia de la API de Aspose.Slides para C++
description: Compara igualdad de punto flotante con tipos aritméticos.
type: docs
weight: 27
url: /es/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) función

Compara igualdad de punto flotante con tipos aritméticos.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
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
| lhs | const T1 | Valor LHS. |
| rhs | const T2 | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) función

Compara igualdad de valores, uno o ambos de los cuales son [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) función

Compara igualdad de tipos no punteros usando el método Equals proporcionado.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) función

Compara igualdad de tipos no punteros usando el método Equals proporcionado.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) función

Compara igualdad de tipos no punteros usando el operador == proporcionado.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) función

Compara igualdad de tipos boxable con valores [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) función

Compara igualdad de tipos boxable con valores [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) función

Compara igualdad de literal de cadena con valores [SmartPtr](../../system/smartptr/) usando desempaquetado.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const char16_t * | Valor LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) función

Compara igualdad de literal de cadena con valores [SmartPtr](../../system/smartptr/) usando desempaquetado.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lhs_expr | const char * | Expresión LHS. |
| rhs_expr | const char * | Expresión RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Valor LHS. |
| rhs | const char16_t * | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) función

Compara igualdad de tipo aleatorio con nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) función

Compara igualdad de tipo aleatorio con nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) función

Compara igualdad de tipos puntero.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) función

Compara igualdad de tipos puntero.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) función

Compara igualdad de un tipo aleatorio con un valor [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
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
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) función

Compara igualdad de un valor [Nullable](../../system/nullable/) con un tipo aleatorio.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
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
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | Valor LHS. |
| rhs | T2 | Valor RHS. |
| s | long long | Un parámetro de servicio que sirve como selector de la implementación de la función; el valor del parámetro se ignora |

### Valor de retorno

Resultado de aserción con estilo gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) función

Compara igualdad de tipos aleatorios usando algoritmos gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) función

Compara igualdad de dos valores [System::String](../../system/string/), protegiendo contra la invocación de una función miembro en un [String](../../system/string/) nulo. Plantillado (en lugar de una sobrecarga sencilla que tome const [String](../../system/string/)&) para que llamadas de tipo mixto — por ejemplo, un literal de cadena char16_t comparado con un [String](../../system/string/) — no puedan deducir un T consistente único y se excluyan de este candidato por completo, en lugar de competir con la plantilla catch-all AreEqualImpl<T1,T2> mediante el parámetro selector long long/int y producir una resolución de sobrecarga ambigua.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| T | Tipo [Object](../../system/object/), limitado a [System::String](../../system/string/). |

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

## Ver también

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
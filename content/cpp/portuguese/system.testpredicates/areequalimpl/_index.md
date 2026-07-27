---
title: AreEqualImpl()
second_title: Referência da API Aspose.Slides for C++
description: Compara igualdade de ponto flutuante com tipos aritméticos.
type: docs
weight: 27
url: /pt/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) função

Compara igualdade de ponto flutuante com tipos aritméticos.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1 | LHS value. |
| rhs | const T2 | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) função

Compara igualdade de valores, um ou ambos sendo [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1& | LHS value. |
| rhs | const T2& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) função

Compara igualdade de tipos não ponteiro usando o método Equals fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T& | LHS value. |
| rhs | const T& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T&, const T&, long long) função

Compara igualdade de tipos não ponteiro usando o método Equals fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T& | LHS value. |
| rhs | const T& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) função

Compara igualdade de tipos não ponteiro usando o operador == fornecido.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T& | LHS value. |
| rhs | const T& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>&, long long) função

Compara igualdade de boxable com valores [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, T, long long) função

Compara igualdade de boxable com valores [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | LHS value. |
| rhs | T | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>&, long long) função

Compara igualdade de literal de string com valores [SmartPtr](../../system/smartptr/) usando unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const char16_t * | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, const char16_t *, long long) função

Compara igualdade de literal de string com valores [SmartPtr](../../system/smartptr/) usando unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | LHS value. |
| rhs | const char16_t * | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) função

Compara igualdade de tipo aleatório com nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) função

Compara igualdade de tipo aleatório com nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) função

Compara igualdade de tipos ponteiro.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1& | LHS value. |
| rhs | const T2& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) função

Compara igualdade de tipos ponteiro.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1& | LHS value. |
| rhs | const T2& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable<T2>&, long long) função

Compara igualdade de um tipo aleatório com um valor [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable<T1>&, T2, long long) função

Compara igualdade de um valor [Nullable](../../system/nullable/) com um tipo aleatório.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>& | LHS value. |
| rhs | T2 | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Valor de retorno

gtest-styled assertion result.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) função

Compara igualdade de tipos aleatórios usando algoritmos gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### Valor de retorno

gtest-styled assertion result.

## Veja Também

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Class [Stream](../../system.io/stream/)
* Class [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
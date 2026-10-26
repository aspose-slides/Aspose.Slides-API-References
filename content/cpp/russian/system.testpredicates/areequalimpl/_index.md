---
title: AreEqualImpl()
second_title: Aspose.Slides для C++ справочник API
description: Сравнивает равенство чисел с плавающей точкой и арифметических типов.
type: docs
weight: 27
url: /ru/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) function

Equal-compares floating point with arithmetic types.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип объекта LHS. |
| T2 | Тип объекта RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1 | Значение LHS. |
| rhs | const T2 | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) function

Equal-compares values one or both of them being [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип объекта LHS. |
| T2 | Тип объекта RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1& | Значение LHS. |
| rhs | const T2& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) function

Equal-compares non-pointer types using Equals method provided.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../system/object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T& | Значение LHS. |
| rhs | const T& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T&, const T&, long long) function

Equal-compares non-pointer types using Equals method provided.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../system/object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T& | Значение LHS. |
| rhs | const T& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) function

Equal-compares non-pointer types using operator == provided.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../system/object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T& | Значение LHS. |
| rhs | const T& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>&, long long) function

Equal-compares boxable with [SmartPtr](../../system/smartptr/) values.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../system/object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T | Значение LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, T, long long) function

Equal-compares boxable with [SmartPtr](../../system/smartptr/) values.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../system/object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | Значение LHS. |
| rhs | T | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>&, long long) function

Equal-compares string literal with [SmartPtr](../../system/smartptr/) values using unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const char16_t * | Значение LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, const char16_t *, long long) function

Equal-compares string literal with [SmartPtr](../../system/smartptr/) values using unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>& | Значение LHS. |
| rhs | const char16_t * | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Equal-compares random type wiht nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../system/object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T | Значение LHS. |
| s | std::nullptr_t | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Equal-compares random type with nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../system/object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| rhs | std::nullptr_t | Значение RHS. |
| s | T | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) function

Equal-compares pointer types.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип LHS. |
| T2 | Тип RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1& | Значение LHS. |
| rhs | const T2& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) function

Equal-compares pointer types.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип LHS. |
| T2 | Тип RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1& | Значение LHS. |
| rhs | const T2& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable<T2>&, long long) function

Equal-compares a random type with a [Nullable](../../system/nullable/) value.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип LHS. |
| T2 | Тип RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T1 | Значение LHS. |
| rhs | const [Nullable](../../system/nullable/)<T2>& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable<T1>&, T2, long long) function

Equal-compares a [Nullable](../../system/nullable/) value with a random type.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип LHS. |
| T2 | Тип RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const [Nullable](../../system/nullable/)<T1>& | Значение LHS. |
| rhs | T2 | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) function

Equal-compares random types using gtest altorithms.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип LHS. |
| T2 | Тип RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T1 | Значение LHS. |
| rhs | T2 | Значение RHS. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) function

Equal-compares two [System::String](../../system/string/) values, guarding against invoking a member function on a null [String](../../system/string/). Templated (rather than a plain overload taking const [String](../../system/string/)&) so that mixed-type calls - e.g. a char16_t string literal compared against a [String](../../system/string/) - fail to deduce a single consistent T and are excluded from this candidate entirely, instead of competing with the catch-all AreEqualImpl<T1,T2> template via the long long/int selector parameter and producing an ambiguous overload resolution.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип [Object](../../system/object/), ограниченный [System::String](../../system/string/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T& | Значение LHS. |
| rhs | const T& | Значение RHS. |
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется. |

### Возвращаемое значение

Результат проверки в стиле gtest.

## See Also

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
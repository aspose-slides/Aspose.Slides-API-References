---
title: AreEqualImpl()
second_title: Aspose.Slides для C++ — справочник API
description: Сравнивает равенством значения с плавающей точкой и арифметические типы.
type: docs
weight: 27
url: /ru/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) функция


Equal-compares floating point with arithmetic types.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | LHS тип объекта. |
| T2 | RHS тип объекта. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const T1 | LHS значение. |
| rhs | const T2 | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) функция


Equal-compares values one or both of them being [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | LHS тип объекта. |
| T2 | RHS тип объекта. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const T1\& | LHS значение. |
| rhs | const T2\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) функция


Equal-compares non-pointer types using Equals method provided.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const T\& | LHS значение. |
| rhs | const T\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) функция


Equal-compares non-pointer types using Equals method provided.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | T\& | LHS значение. |
| rhs | const T\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) функция


Equal-compares non-pointer types using operator == provided.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const T\& | LHS значение. |
| rhs | const T\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) функция


Equal-compares boxable with [SmartPtr](../../system/smartptr/) values.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | T | LHS значение. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) функция


Equal-compares boxable with [SmartPtr](../../system/smartptr/) values.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS значение. |
| rhs | T | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) функция


Equal-compares string literal with [SmartPtr](../../system/smartptr/) values using unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const char16_t * | LHS значение. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) функция


Equal-compares string literal with [SmartPtr](../../system/smartptr/) values using unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS значение. |
| rhs | const char16_t * | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) функция


Equal-compares random type wiht nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | T | LHS значение. |
| s | std::nullptr_t | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) функция


Equal-compares random type with nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| rhs | std::nullptr_t | RHS значение. |
| s | T | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) функция


Equal-compares pointer types.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | LHS тип. |
| T2 | RHS тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const T1\& | LHS значение. |
| rhs | const T2\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) функция


Equal-compares pointer types.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | LHS тип. |
| T2 | RHS тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const T1\& | LHS значение. |
| rhs | const T2\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) функция


Equal-compares a random type with a [Nullable](../../system/nullable/) value.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | LHS тип. |
| T2 | RHS тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | T1 | LHS значение. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) функция


Equal-compares a [Nullable](../../system/nullable/) value with a random type.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | LHS тип. |
| T2 | RHS тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | LHS значение. |
| rhs | T2 | RHS значение. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

результат утверждения в стиле gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) функция


Equal-compares random types using gtest altorithms.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | LHS тип. |
| T2 | RHS тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS выражение. |
| rhs_expr | const char * | RHS выражение. |
| lhs | T1 | LHS значение. |
| rhs | T2 | RHS значение. |

### Возвращаемое значение

результат утверждения в стиле gtest.

## См. также

* Тип [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Тип [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Тип [SharedPtr](../../system/sharedptr/)
* Класс [Object](../../system/object/)
* Класс [Stream](../../system.io/stream/)
* Класс [Nullable](../../system/nullable/)
* Структура [IsSmartPtr](../../system/issmartptr/)
* Структура [IsBoxable](../../system/isboxable/)
* Структура [IsStringByteSequence](../../system/isstringbytesequence/)
* Структура [IsNullable](../../system/isnullable/)
* Пространство имён [System::TestPredicates](../)
* Библиотека [Aspose.Slides](../../)
---
title: AreNotEqualImpl()
second_title: Aspose.Slides для C++ справочник API
description: Сравнение неравенства сравнивает значения, при этом одно или оба из них являются Decimal.
type: docs
weight: 53
url: /ru/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Неравенство сравнивает значения, при этом одно или оба из них являются [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| lhs | const T1\& | Значение LHS. |
| rhs | const T2\& | Значение RHS. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Неравенство сравнивает типы без указателей, используя предоставленный метод Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T\& | Значение LHS. |
| rhs | const T\& | Значение RHS. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) function

Неравенство сравнивает типы без указателей, используя предоставленный метод Equals.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T\& | Значение LHS. |
| rhs | const T\& | Значение RHS. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

Неравенство сравнивает типы без указателей, используя предоставленный оператор !=.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T\& | Значение LHS. |
| rhs | const T\& | Значение RHS. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

Неравенство сравнивает упаковываемый тип с [SmartPtr](../../system/smartptr/) значениями, используя распаковку.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T | Значение LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Значение RHS. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

Неравенство сравнивает упаковываемый тип с [SmartPtr](../../system/smartptr/) значениями, используя распаковку.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | Значение LHS. |
| rhs | T | Значение RHS. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

Неравенство сравнивает произвольный тип с nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T | Значение LHS. |
| s | std::nullptr_t | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

Неравенство сравнивает произвольный тип с nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| rhs | std::nullptr_t | Значение RHS. |
| s | T | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Equal-compares pointer types.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| lhs | const T1\& | Значение LHS. |
| rhs | const T2\& | Значение RHS. |
| s | long long | Сервисный параметр, который служит селектором реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) function

Equal-compares random types using gtest altorithms.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
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

Результат утверждения в стиле gtest.

## Смотрите также

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
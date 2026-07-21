---
title: AreSameImpl()
second_title: Справочник API Aspose.Slides для C++
description: Сравнивает умные указатели.
type: docs
weight: 79
url: /ru/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) функция

Сравнивает умные указатели.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) функция

Сравнивает исключения.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | Сервисный параметр, используемый как селектор реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) функция

Сравнивает значения, не являющиеся указателями.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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

### Возвращаемое значение

Результат утверждения в стиле gtest.

## См. также

* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsExceptionWrapper](../../system/isexceptionwrapper/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
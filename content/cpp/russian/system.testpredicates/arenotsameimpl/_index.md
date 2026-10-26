---
title: AreNotSameImpl()
second_title: Aspose.Slides для C++ справочник API
description: Are-not-same сравнивает умные указатели.
type: docs
weight: 105
url: /ru/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) функция

Are-not-same сравнивает умные указатели.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T1 | Тип объекта LHS. |
| T2 | Тип объекта RHS. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1\& | Значение LHS. |
| rhs | const T2\& | Значение RHS. |
| s | long long | Служебный параметр, который используется в качестве селектора реализации функции; значение параметра игнорируется |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) функция

Are-not-same сравнивает значения, не являющиеся указателями.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T1 | Тип объекта LHS. |
| T2 | Тип объекта RHS. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | const T1\& | Значение LHS. |
| rhs | const T2\& | Значение RHS. |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## См. также

* Структура [IsSmartPtr](../../system/issmartptr/)
* Пространство имён [System::TestPredicates](../)
* Библиотека [Aspose.Slides](../../)
---
title: AreNotEqual()
second_title: Aspose.Slides для C++ справочник API
description: Сравнивает аргументы на неравенство для утверждения AreNotEqual.
type: docs
weight: 131
url: /ru/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1&, const T2&) функция


Сравнивает аргументы на неравенство для утверждения AreNotEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

### Возвращаемое значение

Результат утверждения в стиле gtest.

## Смотрите также

* Пространство имён [System::TestPredicates::Details::SharedPtrAsserts](../)
* Библиотека [Aspose.Slides](../../)
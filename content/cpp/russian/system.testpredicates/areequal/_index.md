---
title: AreEqual()
second_title: Aspose.Slides для C++: справочник API
description: Сравнивает аргументы для утверждения AreEqual.
type: docs
weight: 14
url: /ru/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1&&, T2&&) функция

Сравнивает аргументы для утверждения AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1&& | Значение LHS. |
| rhs | T2&& | Значение RHS. |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## См. также

* Пространство имён [System::TestPredicates](../)
* Библиотека [Aspose.Slides](../../)
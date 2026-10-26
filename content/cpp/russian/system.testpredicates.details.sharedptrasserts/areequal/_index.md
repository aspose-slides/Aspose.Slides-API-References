---
title: AreEqual()
second_title: Aspose.Slides для C++: справочник API
description: Сравнивает аргументы на равенство для утверждения AreEqual.
type: docs
weight: 92
url: /ru/system.testpredicates.details.sharedptrasserts/areequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *, const char *, const T1\&, const T2\&) функция

Сравнивает аргументы на равенство для утверждения AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### Возвращаемое значение

Результат утверждения в стиле gtest.

## См. также

* Пространство имён [System::TestPredicates::Details::SharedPtrAsserts](../)
* Библиотека [Aspose.Slides](../../)
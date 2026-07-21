---
title: AreNotSame()
second_title: Aspose.Slides для C++ справочник API
description: Are-not-same сравнивает аргументы для утверждения AreSame.
type: docs
weight: 92
url: /ru/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) функция


Are-not-same сравнивает аргументы для утверждения AreSame.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

gtest-styled результат утверждения.

## См. также

* Пространство имён [System::TestPredicates](../)
* Библиотека [Aspose.Slides](../../)
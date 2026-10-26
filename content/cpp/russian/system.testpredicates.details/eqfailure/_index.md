---
title: EqFailure()
second_title: Aspose.Slides для C++ справочник API
description: Форматирует ошибку утверждения == для вывода.
type: docs
weight: 27
url: /ru/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) функция


Форматирует ошибку утверждения == для вывода.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Тип значения LHS. |
| T2 | Тип значения RHS. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Выражение LHS. |
| rhs_expr | const char * | Выражение RHS. |
| lhs | T1\& | Значение LHS. |
| rhs | T2\& | Значение RHS. |

### Возвращаемое значение

[Object](../../system/object/) оборачивает текст ошибки.

## См. также

* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)
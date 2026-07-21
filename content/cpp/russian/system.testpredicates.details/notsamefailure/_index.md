---
title: NotSameFailure()
second_title: Aspose.Slides для C++ справки по API
description: Форматирует сообщение об ошибке утверждения 'not same' для вывода.
type: docs
weight: 66
url: /ru/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) функция

Форматирует сообщение об ошибке утверждения 'not same' для вывода.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
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

* Пространство имён [System::TestPredicates::Details](../)
* Библиотека [Aspose.Slides](../../)
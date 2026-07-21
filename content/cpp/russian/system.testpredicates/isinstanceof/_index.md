---
title: IsInstanceOf()
second_title: Aspose.Slides для C++ Справочник API
description: Is-instance-of сравнивает аргументы для проверки утверждения IsInstanceOf.
type: docs
weight: 118
url: /ru/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) функция

Is-instance-of-compares аргументы для утверждения IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип аргумента. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lhs_expr | const char * | Левый операнд. |
| rhs_expr | const char * | Правый операнд. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | Объект typeInfo, представляющий тип, против которого сравнивается тип **obj** |
| obj | const T\& | Объект, тип которого сравнивается с указанным типом |

### Возвращаемое значение

Результат проверки в стиле gtest.

## См. также

* Класс [TypeInfo](../../system/typeinfo/)
* Пространство имён [System::TestPredicates](../)
* Библиотека [Aspose.Slides](../../)
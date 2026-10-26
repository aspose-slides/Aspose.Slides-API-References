---
title: has_print_to_method
second_title: Aspose.Slides для C++: справочник API
description: "Проверяет наличие перегрузки функции PrintTo, принимающей заданный тип в качестве первого аргумента. Если перегрузка существует, наследует std::true_type, иначе наследует std::false_type."
type: docs
weight: 27
url: /ru/system.testpredicates.typetraits/has_print_to_method/
---
## has_print_to_method struct

Проверяет наличие перегрузки функции PrintTo, принимающей заданный тип в качестве первого аргумента. Если перегрузка существует, наследует std::true_type, иначе наследует std::false_type.

```cpp
template<typename T,typename Enable>class has_print_to_method : public std::false_type
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип для проверки. |
| Enable | Формальный аргумент для работы SFINAE. |

## Смотрите также

* Пространство имён [System::TestPredicates::TypeTraits](../)
* Библиотека [Aspose.Slides](../../)
---
title: IsCppContainer
second_title: Aspose.Slides для C++ справочник API
description: "Проверяет, является ли конкретный тип контейнером в стиле STL. Для этого проверяется наличие типов-членов iterator и const_iterator. Если оба присутствуют, наследуется std::true_type, в противном случае наследуется std::false_type."
type: docs
weight: 40
url: /ru/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Проверяет, является ли конкретный тип контейнером в стиле STL. Для этого проверяется наличие типов-членов iterator и const_iterator. Если оба присутствуют, наследуется std::true_type, в противном случае наследуется std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип для проверки. |
| Enable | Формальный аргумент для работы SFINAE. |

## См. также

* Пространство имён [System::TestPredicates::TypeTraits](../)
* Библиотека [Aspose.Slides](../../)
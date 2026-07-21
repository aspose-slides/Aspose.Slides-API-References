---
title: has_method_compareto
second_title: Справочник API Aspose.Slides для C++
description: "Проверяет, существует ли метод CompareTo в указанном типе. Если да, наследуется от std::true_type, в противном случае — от std::false_type. Можно использовать в std::enable_if."
type: docs
weight: 170
url: /ru/system.collections.generic.details/has_method_compareto/
---
## has_method_compareto struct

Проверяет, существует ли метод CompareTo в указанном типе. Если да, наследуется от std::true_type, в противном случае — от std::false_type. Может использоваться в std::enable_if.

```cpp
template<typename T,typename Sfinae>class has_method_compareto : public std::false_type
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, для проверки наличия метода Equals. |
| Sfinae | Формальный шаблонный аргумент, необходимый для работы SFINAE. |

## См. также

* Пространство имён [System::Collections::Generic::Details](../)
* Библиотека [Aspose.Slides](../../)
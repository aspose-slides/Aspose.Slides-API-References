---
title: has_method_compareto_shared_ptr
second_title: Aspose.Slides для C++ справка API
description: "Проверяет, существует ли метод CompareTo(SharedPtr<T>) в указанном типе. Если да, наследует std::true_type, иначе наследует std::false_type. Может использоваться в std::enable_if."
type: docs
weight: 183
url: /ru/system.collections.generic.details/has_method_compareto_shared_ptr/
---
## has_method_compareto_shared_ptr struct

Проверяет, существует ли метод CompareTo(SharedPtr<T>) в указанном типе. Если да, наследует std::true_type, иначе наследует std::false_type. Может использоваться в std::enable_if.

```cpp
template<typename T,typename Sfinae>class has_method_compareto_shared_ptr : public std::false_type
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, для которого проверяется наличие метода Equals. |
| Sfinae | Формальный параметр шаблона, необходимый для работы SFINAE. |

## См. также

* Пространство имён [System::Collections::Generic::Details](../)
* Библиотека [Aspose.Slides](../../)
---
title: IsBoxable
second_title: Справочник API Aspose.Slides для C++
description: Шаблонный предикат, проверяющий, поддерживается ли упаковка указанного типа.
type: docs
weight: 1639
url: /ru/system/isboxable/
---
## IsBoxable структура


Шаблонный предикат, проверяющий, поддерживается ли упаковка указанного типа.

```cpp
template<typename T>class IsBoxable : public std::integral_constant<bool, std::is_base_of<Details::BoxableObjectBase, T>::value||std::is_arithmetic<T>::value||std::is_enum<T>::value>
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип для проверки |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)
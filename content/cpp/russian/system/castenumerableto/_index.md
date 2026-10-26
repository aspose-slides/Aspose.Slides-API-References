---
title: CastEnumerableTo()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет явное приведение элементов указанного перечисляемого объекта к другому типу.
type: docs
weight: 2926
url: /ru/system/castenumerableto/
---
## System::CastEnumerableTo(const From&) функция

Выполняет явное приведение элементов указанного перечисляемого объекта к другому типу.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| To | Тип, к которому статически приводятся элементы перечисляемого объекта |
| From | Тип перечисляемого объекта |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| enumerable | const From\& | Объект enumerable, содержащий элементы для приведения |

### Возвращаемое значение

Указатель на новую коллекцию, содержащую элементы типа **To**, эквивалентные элементам **enumerable**.

## System::CastEnumerableTo(const From&) функция

Выполняет явное приведение элементов указанного перечисляемого объекта к другому типу.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| To | Тип, к которому статически приводятся элементы перечисляемого объекта |
| From | Тип перечисляемого объекта |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| enumerable | const From\& | Является наследником объекта Enumerable с определённым методом get_Count и содержащим элементы для приведения |

### Возвращаемое значение

Указатель на новую коллекцию, содержащую элементы типа **To**, эквивалентные элементам **enumerable**.

## См. также

* Класс [ListPtr](../../system.collections.generic/listptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)
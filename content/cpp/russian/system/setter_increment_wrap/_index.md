---
title: setter_increment_wrap()
second_title: Aspose.Slides для C++ справочник API
description: Переводчик преобразует выражения инкремента C#, нацеленные на свойство класса, имеющее определённые сеттер и геттер, в вызов этой функции.
type: docs
weight: 2796
url: /ru/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) функция

Переводчик преобразует выражения инкремента C#, нацеленные на свойство класса, которое имеет определённые сеттер и геттер, в вызов этой функции.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип свойства |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pGetter | T(*)() | Указатель на функцию, указывающая на свободную функцию-геттер свойства |
| pSetter | void(*)(T) | Указатель на функцию, указывающая на свободную функцию-сеттер свойства |

### Возвращаемое значение

Увеличенное значение свойства

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) функция

Переводчик преобразует выражения инкремента C#, нацеленные на свойство класса, которое имеет определённые сеттер и геттер, в вызов этой функции.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип свойства |
| Host | - класс экземпляра, который будет изменён |
| HostGet | - сам Host или его базовый тип, где определён геттер свойства |
| HostSet | - сам Host или его базовый тип, где определён сеттер свойства |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | Host *const | Указатель на объект, свойство которого будет инкрементировано |
| pGetter | T(HostGet::*)() | Указатель на функцию, указывающая на метод-геттер свойства |
| pSetter | void(HostSet::*)(T) | Указатель на функцию, указывающая на метод-сеттер свойства |

### Возвращаемое значение

Увеличенное значение свойства

## Смотрите также

* Namespace [System](../)
* Library [Aspose.Slides](../../)
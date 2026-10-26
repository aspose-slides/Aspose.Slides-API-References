---
title: setter_post_increment_wrap()
second_title: Справочник API Aspose.Slides для C++
description: Переводчик преобразует постинкрементные выражения C#, направленные на свойство класса, для которого определены сеттер и геттер, в вызов этой функции.
type: docs
weight: 2809
url: /ru/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) function

Переводчик преобразует постинкрементные выражения C# , направленные на свойство класса, для которого определены сеттер и геттер, в вызов этой функции.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип свойства |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pGetter | T(*)() | Указатель на функцию, указывающую на свободную функцию-геттер свойства |
| pSetter | void(*)(T) | Указатель на функцию, указывающую на свободную функцию-сеттер свойства |

### Возвращаемое значение

Значение свойства до инкрементирования

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function

Переводчик преобразует постинкрементные выражения C# , направленные на свойство экземпляра, для которого определены сеттер и геттер, в вызов этой функции (перегрузка для негорнозного геттера).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип свойства. |
| Host | - класс экземпляра, который следует изменить |
| HostGet | - сам Host или его базовый тип, где определён геттер свойства |
| HostSet | - сам Host или его базовый тип, где определён сеттер свойства |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | Host *const | Экземпляр, для которого вызываются геттеры и сеттеры. |
| pGetter | T(HostGet::*)() | Указатель на функцию, указывающую на функцию-геттер свойства |
| pSetter | void(HostSet::*)(T) | Указатель на функцию, указывающую на функцию-сеттер свойства |

### Возвращаемое значение

Значение свойства до инкрементирования

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function

Переводчик преобразует постинкрементные выражения C# , направленные на свойство экземпляра, для которого определены сеттер и геттер, в вызов этой функции (перегрузка для константного геттера).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип свойства. |
| Host | - класс экземпляра, который следует изменить |
| HostConstGet | - сам Host или его базовый тип, где определён геттер свойства |
| HostSet | - сам Host или его базовый тип, где определён сеттер свойства |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | Host *const | Экземпляр, для которого вызываются геттеры и сеттеры. |
| pGetter | T(HostConstGet::*)() const | Указатель на функцию, указывающую на функцию-геттер свойства |
| pSetter | void(HostSet::*)(T) | Указатель на функцию, указывающую на функцию-сеттер свойства |

### Возвращаемое значение

Значение свойства до инкрементирования

## См. также

* Namespace [System](../)
* Library [Aspose.Slides](../../)
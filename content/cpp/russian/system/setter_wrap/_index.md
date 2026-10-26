---
title: setter_wrap()
second_title: Справочник API Aspose.Slides для C++
description: Перегрузка для статических функций-установщиков с преобразованием типов.
type: docs
weight: 2783
url: /ru/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) функция

Перегрузка для статических функций-установщиков с преобразованием типов.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения. |
| T2 | Тип, ожидаемый функцией-установщиком. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pSetter | void(*)(T2) | Ссылка на статическую функцию-установщик. |
| value | T | Значение для установки. |

### Возвращаемое значение

устанавливает значение.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) функция

Перегрузка для функций-установщиков экземпляра с преобразованием типов.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения. |
| T2 | Тип, ожидаемый функцией-установщиком. |
| Host | Тип экземпляра. |
| HostSet | - Сам Host или его базовый тип, где определён сеттер свойства. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | Host *const | [Object](../object/) для вызова функции-установщика. |
| pSetter | void(HostSet::*)(T2) | Ссылка на функцию-установщик. |
| value | T | Значение для установки. |

### Возвращаемое значение

устанавливает значение.

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)
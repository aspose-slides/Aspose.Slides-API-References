---
title: Func()
second_title: Aspose.Slides для C++: справочник API
description: Конструктор по умолчанию, создающий null-Func.
type: docs
weight: 1
url: /ru/system/func/func/
---
## Func::Func() конструктор

Конструктор по умолчанию, создающий null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) конструктор

Конструктор, создающий объект [Func](../) и присваивающий ему значение (либо фактический обратный вызов, либо nullptr).

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип аргумента. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| arg | T\&& | Аргумент. |

## Func::Func(const Func\&) конструктор

Конструктор копирования.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) для копирования данных из. |

## Func::Func(Func\&&) конструктор

Конструктор перемещения.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) для перемещения данных из. |

## См. также

* Класс [Func](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)
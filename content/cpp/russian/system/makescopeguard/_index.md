---
title: MakeScopeGuard()
second_title: Aspose.Slides для C++ справочник API
description: Фабричная функция, создающая экземпляры класса ScopedGuard.
type: docs
weight: 2770
url: /ru/system/makescopeguard/
---
## System::MakeScopeGuard(F) функция

Фабричная функция, создающая экземпляры класса ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| The | тип объектa функции, который будет вызван построенным объектом ScopedGuard |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| f | F | Объект функции, передаваемый в конструктор класса ScopedGuard. |

### Возвращаемое значение

Новый экземпляр класса ScopedGuard

## Смотрите также

* Структура [ScopeGuard](../scopeguard/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)
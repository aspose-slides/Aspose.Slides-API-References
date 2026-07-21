---
title: UnknownIsNull()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для не скалярных типов.
type: docs
weight: 144
url: /ru/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) метод

Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для не скалярных типов.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T | [Object](../../object/) для проверки. |

### Возвращаемое значение

True, если 'obj == nullptr' истинно, иначе false.

## ObjectExt::UnknownIsNull(T) метод

Проверяет, является ли объект неизвестного типа nullptr. Перегрузка для скалярных типов.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T | [Object](../../object/) для проверки. |

### Возвращаемое значение

Всегда возвращает false.

## См. также

* Класс [ObjectExt](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)
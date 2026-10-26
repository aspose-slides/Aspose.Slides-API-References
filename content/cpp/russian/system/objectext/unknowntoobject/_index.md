---
title: UnknownToObject()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует неизвестный тип в Object, обрабатывая как тип умного указателя, так и тип значения.
type: docs
weight: 118
url: /ru/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) метод

Преобразует неизвестный тип в [Object](../../object/), обрабатывая как тип умного указателя, так и тип значения.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип для преобразования в [Object](../../object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T | [Object](../../object/) для преобразования. |

### Возвращаемое значение

Умный указатель на [Object](../../object/), являющийся либо преобразованным указателем, либо упакованным значением.

## ObjectExt::UnknownToObject(const T\&) метод

Преобразует неизвестный тип в [Object](../../object/), обрабатывая как тип умного указателя, так и тип значения.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип для преобразования в [Object](../../object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для преобразования. |

### Возвращаемое значение

Умный указатель на [Object](../../object/), являющийся либо преобразованным указателем, либо упакованным значением.

## См. также

* Класс [SmartPtr](../../smartptr/)
* Класс [Object](../../object/)
* Класс [ObjectExt](../)
* Структура [IsSmartPtr](../../issmartptr/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)
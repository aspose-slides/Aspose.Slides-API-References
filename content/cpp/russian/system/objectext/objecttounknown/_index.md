---
title: ObjectToUnknown()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует Object в неизвестный тип, обрабатывая как тип умного указателя, так и упакованное значение.
type: docs
weight: 131
url: /ru/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) метод

Преобразует [Object](../../object/) в неизвестный тип, обрабатывая как тип умного указателя, так и упакованное значение.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, в который преобразуется [Object](../../object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) для преобразования. |

### Возвращаемое значение

Либо неупакованное значение, либо преобразованный указатель.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) метод

Преобразует [Object](../../object/) в неизвестный тип, обрабатывая как тип умного указателя, так и упакованное значение.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, в который преобразуется [Object](../../object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) для преобразования. |

### Возвращаемое значение

Либо неупакованное значение, либо преобразованный указатель.

## См. также

* Класс [SmartPtr](../../smartptr/)
* Класс [Object](../../object/)
* Класс [ObjectExt](../)
* Структура [IsSmartPtr](../../issmartptr/)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)
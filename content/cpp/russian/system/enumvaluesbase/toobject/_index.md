---
title: ToObject()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует указанное 64-битное беззнаковое целое значение в член перечисления.
type: docs
weight: 40
url: /ru/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) метод


Преобразует указанное 64-битное беззнаковое целое значение в член перечисления.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Тип перечисления, который нужно вернуть. |
| value | **uint64_t** | Значение, которое нужно преобразовать в член перечисления. |

### Возвращаемое значение

Экземпляр перечисления, установленный в значение.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) метод


Преобразует указанный объект с целочисленным значением в член перечисления.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Тип перечисления, который нужно вернуть. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Значение, преобразуемое в член перечисления. |

### Возвращаемое значение

Объект перечисления, значение которого равно value.

## См. также

* Тип [SharedPtr](../../sharedptr/)
* Класс [Object](../../object/)
* Класс [TypeInfo](../../typeinfo/)
* Класс [EnumValuesBase](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)
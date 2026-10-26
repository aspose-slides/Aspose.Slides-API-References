---
title: GetCustomAttributes()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу, представляемому текущим объектом.
type: docs
weight: 66
url: /ru/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const метод


Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу, представляемому текущим объектом.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Тип атрибута, который требуется найти. |
| inherit | **bool** | Нужно ли также проверять унаследованные атрибуты. |

## MemberInfo::GetCustomAttributes(bool) const метод


Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу, представляемому текущим объектом.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| inherit | **bool** | Нужно ли также проверять унаследованные атрибуты. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [TypeInfo](../../../system/typeinfo/)
* Класс [MemberInfo](../)
* Пространство имён [System::Reflection](../../)
* Library [Aspose.Slides](../../../)
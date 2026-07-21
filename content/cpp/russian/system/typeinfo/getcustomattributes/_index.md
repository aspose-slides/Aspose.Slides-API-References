---
title: GetCustomAttributes()
second_title: Aspose.Slides для C++ API Reference
description: Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу.
type: docs
weight: 586
url: /ru/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const метод

Возвращает массив, содержащий объекты, представляющие все пользовательские атрибуты, применённые к типу.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```
## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const метод

Возвращает массив, содержащий объекты, представляющие конкретные атрибуты, применённые к типу.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Тип атрибута, который нужно искать. |
| inherit | **bool** | Нужно ли также искать унаследованные атрибуты. |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Класс [SmartPtr](../../smartptr/)
* Класс [TypeInfo](../)
* Пространство имен [System](../../)
* Библиотека [Aspose.Slides](../../../)
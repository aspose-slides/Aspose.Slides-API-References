---
title: GetCustomAttribute()
second_title: Aspose.Slides для справочника API C++
description: Возвращает пользовательский атрибут указанного типа, применённый к указанному типу.
type: docs
weight: 1
url: /ru/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) метод

Возвращает пользовательский атрибут указанного типа, применённый к указанному типу.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Тип атрибута, который извлекается |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Тип атрибута, который необходимо получить |

### Возвращаемое значение

Полученный атрибут или null, если указанный тип не имеет атрибута указанного типа.

## См. также

* typedef [ptr](../../object/ptr/)
* Класс [TypeInfo](../../typeinfo/)
* Класс [Attribute](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)
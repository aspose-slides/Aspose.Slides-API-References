---
title: TypeInfoPtr
second_title: Aspose.Slides для справочника API C++
description: "Обёртка для указателя на экземпляр класса TypeInfo. Этот тип должен быть выделен в стеке и передан в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 1925
url: /ru/system/typeinfoptr/
---
## TypeInfoPtr структура

Wrapper for a pointer to an instance of [TypeInfo](../typeinfo/) class. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class TypeInfoPtr
```

## Методы

| Method | Description |
| --- | --- |
|  [operator TypeInfo *](./operator_typeinfo__star/)() | Возвращает необработанный указатель на представленный объект [TypeInfo](../typeinfo/). |
|  [TypeInfoPtr](./typeinfoptr/)() | Конструктор по умолчанию. |
|  [TypeInfoPtr](./typeinfoptr/)(const std::type_info\&) | Конструктор. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *, **uint32_t**) | Конструктор. |
|  [TypeInfoPtr](./typeinfoptr/)(const char_t *) | Конструктор. |
|  [TypeInfoPtr](./typeinfoptr/)(const [String](../string/)\&) | Конструктор. |
|  [~TypeInfoPtr](./~typeinfoptr/)() | Деструктор. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)
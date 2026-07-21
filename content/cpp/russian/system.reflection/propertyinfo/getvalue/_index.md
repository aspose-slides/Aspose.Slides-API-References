---
title: GetValue()
second_title: Aspose.Slides для C++ справочник API
description: Получает значение свойства из конкретного объекта.
type: docs
weight: 1
url: /ru/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) метод

Получает значение свойства из конкретного объекта.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) для чтения свойства из. |

### Возвращаемое значение

Значение указанного свойства для указанного объекта.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) метод

Получает значение свойства из конкретного объекта.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) для чтения свойства из. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Это опциональные индексные значения для индексированных свойств. Для неиндексированных свойств это значение должно быть null. |

### Возвращаемое значение

Значение указанного свойства для указанного объекта.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)
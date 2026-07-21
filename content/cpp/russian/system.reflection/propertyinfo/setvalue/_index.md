---
title: SetValue()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает значение свойства для конкретного объекта.
type: docs
weight: 14
url: /ru/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) метод

Устанавливает значение свойства для конкретного объекта.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) для записи свойства. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Значение свойства для установки. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) метод

Устанавливает значение свойства для конкретного объекта.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) для записи свойства. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Это необязательные значения индекса для индексированных свойств. Для неиндексированных свойств это значение должно быть null. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Значение свойства для установки. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Object](../../../system/object/)
* Класс [PropertyInfo](../)
* Пространство имен [System::Reflection](../../)
* Библиотека [Aspose.Slides](../../../)
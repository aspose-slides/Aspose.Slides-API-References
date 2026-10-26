---
title: Convert()
second_title: Aspose.Slides для C++: Справочник API
description: "Преобразует значение в указанный System::TypeInfo."
type: docs
weight: 1
url: /ru/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) метод

Преобразует значение в заданный [System::TypeInfo](../../../system/typeinfo/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Объект, который будет преобразован. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Тип [System::TypeInfo](../../../system/typeinfo/), в который будет преобразовано значение. |

### Возвращаемое значение

Преобразованное значение.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) метод

Преобразует значение в заданный [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Объект, который будет преобразован. |
| typeCode | [TypeCode](../../../system/typecode/) | Тип [System::TypeCode](../../../system/typecode/), в который будет преобразовано значение. |

### Возвращаемое значение

Преобразованное значение.

## См. также

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
---
title: Convert()
second_title: Aspose.Slides для C++ справочник API
description: Информация RTTI.
type: docs
weight: 1
url: /ru/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


Информация RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Объект, подлежащий преобразованию. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Тип [System::TypeInfo](../../../system/typeinfo/), в который будет преобразовано значение. |

### Return Value

Преобразованное значение.

## Remarks


Преобразует значение в указанный [System::TypeInfo](../../../system/typeinfo/).

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Преобразует значение в указанный [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Объект, подлежащий преобразованию. |
| typeCode | [TypeCode](../../../system/typecode/) | Тип [System::TypeCode](../../../system/typecode/), в который будет преобразовано значение. |

### Return Value

Преобразованное значение.

## See Also

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
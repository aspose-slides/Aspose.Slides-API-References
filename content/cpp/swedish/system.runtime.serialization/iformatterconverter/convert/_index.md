---
title: Convert()
second_title: Aspose.Slides för C++ API-referens
description: RTTI-information.
type: docs
weight: 1
url: /sv/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) metod

RTTI information.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objektet som ska konverteras. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Den [System::TypeInfo](../../../system/typeinfo/) som värdet ska konverteras till. |

### Returvärde

Det konverterade värdet.

## Anmärkningar

Konverterar ett värde till den givna [System::TypeInfo](../../../system/typeinfo/).

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) metod

Konverterar ett värde till den givna [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objektet som ska konverteras. |
| typeCode | [TypeCode](../../../system/typecode/) | Den [System::TypeCode](../../../system/typecode/) som värdet ska konverteras till. |

### Returvärde

Det konverterade värdet.

## Se även

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [IFormatterConverter](../)
* Namnrymd [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
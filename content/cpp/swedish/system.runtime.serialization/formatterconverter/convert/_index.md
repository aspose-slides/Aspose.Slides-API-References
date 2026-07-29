---
title: Convert()
second_title: Aspose.Slides för C++ API-referens
description: "Konverterar ett värde till den angivna System::TypeInfo."
type: docs
weight: 1
url: /sv/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


Konverterar ett värde till den angivna [System::TypeInfo](../../../system/typeinfo/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Objektet som ska konverteras. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Den [System::TypeInfo](../../../system/typeinfo/) som värdet ska konverteras till. |

### Returvärde

Det konverterade värdet.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Konverterar ett värde till den angivna [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
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
* Klass [FormatterConverter](../)
* Namnrymd [System::Runtime::Serialization](../../)
* Bibliotek [Aspose.Slides](../../../)
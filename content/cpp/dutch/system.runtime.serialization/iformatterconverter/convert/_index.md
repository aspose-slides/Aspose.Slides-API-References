---
title: Convert()
second_title: Aspose.Slides voor C++ API-referentie
description: RTTI-informatie.
type: docs
weight: 1
url: /nl/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method

RTTI-informatie.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Het object dat moet worden geconverteerd. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | De [System::TypeInfo](../../../system/typeinfo/) waarin de waarde moet worden geconverteerd. |

### Retourwaarde

De geconverteerde waarde.
## Opmerkingen

Converteert een waarde naar de opgegeven [System::TypeInfo](../../../system/typeinfo/). 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method

Converteert een waarde naar de opgegeven [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Het object dat moet worden geconverteerd. |
| typeCode | [TypeCode](../../../system/typecode/) | De [System::TypeCode](../../../system/typecode/) waarin de waarde moet worden geconverteerd. |

### Retourwaarde

De geconverteerde waarde.

## Zie ook

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
---
title: Convert()
second_title: Aspose.Slides voor C++ API-referentie
description: "Converteert een waarde naar de opgegeven System::TypeInfo."
type: docs
weight: 1
url: /nl/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method

Zet een waarde om naar de opgegeven [System::TypeInfo](../../../system/typeinfo/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Het object dat moet worden geconverteerd. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | De [System::TypeInfo](../../../system/typeinfo/) waarin de waarde moet worden geconverteerd. |

### Retourwaarde

De geconverteerde waarde.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method

Zet een waarde om naar de opgegeven [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
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
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [FormatterConverter](../)
* Naamruimte [System::Runtime::Serialization](../../)
* Bibliotheek [Aspose.Slides](../../../)
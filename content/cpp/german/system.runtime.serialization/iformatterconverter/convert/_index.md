---
title: Convert()
second_title: Aspose.Slides für C++ API Referenz
description: RTTI-Informationen.
type: docs
weight: 1
url: /de/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) Methode


RTTI-Informationen.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Das zu konvertierende Objekt. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Der [System::TypeInfo](../../../system/typeinfo/), in den der Wert konvertiert werden soll. |

### Rückgabewert

Der konvertierte Wert.
## Hinweise


Konvertiert einen Wert in das angegebene [System::TypeInfo](../../../system/typeinfo/). 
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) Methode


Konvertiert einen Wert in das angegebene [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Das zu konvertierende Objekt. |
| typeCode | [TypeCode](../../../system/typecode/) | Der [System::TypeCode](../../../system/typecode/), in den der Wert konvertiert werden soll. |

### Rückgabewert

Der konvertierte Wert.

## Siehe auch

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
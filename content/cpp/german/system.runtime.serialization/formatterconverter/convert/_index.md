---
title: Convert()
second_title: Aspose.Slides für C++ API-Referenz
description: "Konvertiert einen Wert in das angegebene System::TypeInfo."
type: docs
weight: 1
url: /de/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


Konvertiert einen Wert in das angegebene [System::TypeInfo](../../../system/typeinfo/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Das zu konvertierende Objekt. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Der [System::TypeInfo](../../../system/typeinfo/), in den der Wert konvertiert werden soll. |

### Rückgabewert

Der konvertierte Wert.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Konvertiert einen Wert in das angegebene [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
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
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [FormatterConverter](../)
* Namensraum [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
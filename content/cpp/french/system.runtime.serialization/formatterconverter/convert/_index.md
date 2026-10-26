---
title: Convert()
second_title: Référence API Aspose.Slides pour C++
description: "Convertit une valeur en le System::TypeInfo donné."
type: docs
weight: 1
url: /fr/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


Convertit une valeur en le [System::TypeInfo](../../../system/typeinfo/) spécifié.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L'objet à convertir. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Le [System::TypeInfo](../../../system/typeinfo/) dans lequel la valeur doit être convertie. |

### Valeur de retour

La valeur convertie.

## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Convertit une valeur en le [System::TypeCode](../../../system/typecode/) spécifié.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L'objet à convertir. |
| typeCode | [TypeCode](../../../system/typecode/) | Le [System::TypeCode](../../../system/typecode/) dans lequel la valeur doit être convertie. |

### Valeur de retour

La valeur convertie.

## Voir aussi

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.Slides](../../../)
---
title: Convert()
second_title: Référence de l'API Aspose.Slides pour C++
description: Informations RTTI.
type: docs
weight: 1
url: /fr/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) méthode

Informations RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L'objet à convertir. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Le [System::TypeInfo](../../../system/typeinfo/) dans lequel value doit être converti. |

### Valeur de retour

La valeur convertie.

## Remarques

Convertit une valeur en le [System::TypeInfo](../../../system/typeinfo/) spécifié.

## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) méthode

Convertit une valeur en le [System::TypeCode](../../../system/typecode/) donné.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | L'objet à convertir. |
| typeCode | [TypeCode](../../../system/typecode/) | Le [System::TypeCode](../../../system/typecode/) dans lequel value doit être converti. |

### Valeur de retour

La valeur convertie.

## Voir aussi

* Enum [TypeCode](../../../system/typecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IFormatterConverter](../)
* Espace de noms [System::Runtime::Serialization](../../)
* Bibliothèque [Aspose.Slides](../../../)
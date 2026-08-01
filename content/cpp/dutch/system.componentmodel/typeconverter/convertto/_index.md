---
title: ConvertTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert object naar een specifiek type.
type: docs
weight: 53
url: /nl/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) methode

Converteert een object naar een specifiek type.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) om te converteren. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Type om naar te converteren. |

### Retourwaarde

Geconverteerd object.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) methode

Converteert een object naar een specifiek type.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informatie over de conversiecontext. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultuur die moet worden gebruikt bij het converteren van objecten. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) om te converteren. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Type om naar te converteren. |

### Retourwaarde

Geconverteerd object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [TypeConverter](../)
* Klasse [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Naamruimte [System::ComponentModel](../../)
* Bibliotheek [Aspose.Slides](../../../)
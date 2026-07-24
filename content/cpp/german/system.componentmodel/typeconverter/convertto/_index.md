---
title: ConvertTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert ein Objekt in einen bestimmten Typ.
type: docs
weight: 53
url: /de/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method

Konvertiert ein Objekt in einen bestimmten Typ.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) zum Konvertieren. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, in den konvertiert werden soll. |

### Rückgabewert

Konvertiertes Objekt.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method

Konvertiert ein Objekt in einen bestimmten Typ.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) Informationen zum Konvertierungskontext. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur, die beim Konvertieren von Objekten verwendet wird. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) zum Konvertieren. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, in den konvertiert werden soll. |

### Rückgabewert

Konvertiertes Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [TypeConverter](../)
* Class [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)
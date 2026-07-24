---
title: ConvertTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert das Objekt in einen bestimmten Typ.
type: docs
weight: 14
url: /de/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) Methode

Konvertiert das Objekt in einen bestimmten Typ.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) Kontextinformationen für die Konvertierung |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur, die bei der Konvertierung von Objekten verwendet wird |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Ein Objekt, das konvertiert werden soll. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Ein Typ, zu dem konvertiert werden soll. |

### Rückgabewert

Konvertiertes Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [ImageConverter](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)
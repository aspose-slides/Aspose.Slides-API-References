---
title: ConvertTo()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert ein Objekt in einen bestimmten Typ.
type: docs
weight: 14
url: /de/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) Methode

Konvertiert ein Objekt in einen bestimmten Typ.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) Konvertierungs-Kontextinformationen. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur, die beim Konvertieren von Objekten verwendet wird. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Ein Objekt zum Konvertieren. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, in den konvertiert werden soll. |

### Rückgabewert

Konvertiertes Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [FontConverter](../)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
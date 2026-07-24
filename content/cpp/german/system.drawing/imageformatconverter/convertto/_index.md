---
title: ConvertTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert das Objekt in einen bestimmten Typ.
type: docs
weight: 27
url: /de/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) Methode


Konvertiert das Objekt in einen bestimmten Typ.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) Konvertierungskontextinformationen. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur, die beim Konvertieren von Objekten verwendet wird. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) zu konvertieren. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Typ, in den konvertiert werden soll. |

### Rückgabewert

Konvertiertes Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [ImageFormatConverter](../)
* Namensraum [System::Drawing](../../)
* Bibliothek [Aspose.Slides](../../../)
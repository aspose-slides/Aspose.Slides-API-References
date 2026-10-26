---
title: ConvertTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert object naar een specifiek type.
type: docs
weight: 27
url: /nl/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) methode

Converteert object naar een specifiek type.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informatie over de conversie-context. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultuur die wordt gebruikt bij het converteren van objecten. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) om te converteren. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Type om naar te converteren. |

### Retourwaarde

Geconverteerd object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [ImageFormatConverter](../)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)
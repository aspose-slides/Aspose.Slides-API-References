---
title: ConvertTo()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert object naar een specifiek type.
type: docs
weight: 14
url: /nl/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) methode


Converteert object naar een specifiek type.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informatie over de conversiecontext |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture die moet worden gebruikt bij het converteren van objecten |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Een object om te converteren. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Een type om naar te converteren. |

### Retourwaarde

Geconverteerd object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [ImageConverter](../)
* Namespace [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)
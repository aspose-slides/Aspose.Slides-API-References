---
title: ConvertTo()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar objekt till en specifik typ.
type: docs
weight: 14
url: /sv/system.drawing/imageconverter/convertto/
---
## ImageConverter::ConvertTo(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Konverterar objekt till en specifik typ.

```cpp
System::SharedPtr<System::Object> System::Drawing::ImageConverter::ConvertTo(const System::SharedPtr<System::ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[System::ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) konverteringskontextinformation |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur att använda vid konvertering av objekt |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Ett objekt att konvertera. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | En typ att konvertera till. |

### Returvärde

Konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [ImageConverter](../)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)
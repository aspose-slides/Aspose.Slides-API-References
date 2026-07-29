---
title: ConvertTo()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar objekt till en specifik typ.
type: docs
weight: 27
url: /sv/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) metod

Konverterar objekt till en specifik typ.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) information om konverteringskontext. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur som ska användas vid konvertering av objekt. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) för att konvertera. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Typ att konvertera till. |

### Returvärde

Konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [ImageFormatConverter](../)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)
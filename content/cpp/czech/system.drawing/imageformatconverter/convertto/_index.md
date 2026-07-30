---
title: ConvertTo()
second_title: Aspose.Slides pro C++ – reference API
description: Převádí objekt na konkrétní typ.
type: docs
weight: 27
url: /cs/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) metoda

Převádí objekt na konkrétní typ.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informace o kontextu konverze. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura použita při převodu objektů. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) k převodu. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Typ, do kterého se má převést. |

### Návratová hodnota

Převedený objekt.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [Object](../../../system/object/)
* třída [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* třída [CultureInfo](../../../system.globalization/cultureinfo/)
* třída [TypeInfo](../../../system/typeinfo/)
* třída [ImageFormatConverter](../)
* jmenný prostor [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
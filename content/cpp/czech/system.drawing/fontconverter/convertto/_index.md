---
title: ConvertTo()
second_title: Aspose.Slides pro C++ – reference API
description: Převede objekt na konkrétní typ.
type: docs
weight: 14
url: /cs/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metoda

Převede objekt na konkrétní typ.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informace o kontextu konverze. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura, která se použije při konverzi objektů. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Objekt, který se má převést. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, na který se má převést. |

### Návratová hodnota

Převedený objekt.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [FontConverter](../)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)
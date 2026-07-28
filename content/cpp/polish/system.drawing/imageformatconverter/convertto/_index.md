---
title: ConvertTo()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Konwertuje obiekt na określony typ.
type: docs
weight: 27
url: /pl/system.drawing/imageformatconverter/convertto/
---
## ImageFormatConverter::ConvertTo(const SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, const SharedPtr\<Object\>\&, const TypeInfo\&) metoda

Konwertuje obiekt na określony typ.

```cpp
SharedPtr<Object> System::Drawing::ImageFormatConverter::ConvertTo(const SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const SharedPtr<Globalization::CultureInfo> &culture, const SharedPtr<Object> &value, const TypeInfo &destinationType) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje kontekstu konwersji. |
| culture | const [SharedPtr](../../../system/sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana przy konwertowaniu obiektów. |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | [Object](../../../system/object/) do konwersji. |
| destinationType | const [TypeInfo](../../../system/typeinfo/)\& | Typ, na który konwertować. |

### Wartość zwracana

Skonwertowany obiekt.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [ImageFormatConverter](../)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)
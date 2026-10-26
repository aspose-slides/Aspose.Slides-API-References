---
title: ConvertTo()
second_title: Aspose.Slides dla C++ – Referencja API
description: Konwertuje obiekt do określonego typu.
type: docs
weight: 14
url: /pl/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Konwertuje obiekt do określonego typu.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje o kontekście konwersji. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana przy konwertowaniu obiektów. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Obiekt do konwersji. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, do którego ma być konwertowany. |

### Wartość zwracana

Skonwertowany obiekt.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [FontConverter](../)
* Przestrzeń nazw [System::Drawing](../../)
* Library [Aspose.Slides](../../../)
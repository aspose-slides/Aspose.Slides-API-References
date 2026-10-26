---
title: ConvertTo()
second_title: Referencja API Aspose.Slides dla C++
description: Konwertuje obiekt na określony typ.
type: docs
weight: 53
url: /pl/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metoda

Konwertuje obiekt na określony typ.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) do konwersji. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, na który ma zostać skonwertowany. |

### Wartość zwracana

Skonwertowany obiekt.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metoda

Konwertuje obiekt na określony typ.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje o kontekście konwersji. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana przy konwersji obiektów. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) do konwersji. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, na który ma zostać skonwertowany. |

### Wartość zwracana

Skonwertowany obiekt.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [TypeConverter](../)
* Klasa [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System::ComponentModel](../../)
* Biblioteka [Aspose.Slides](../../../)
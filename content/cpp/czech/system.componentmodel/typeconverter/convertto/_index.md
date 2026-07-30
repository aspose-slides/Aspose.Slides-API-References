---
title: ConvertTo()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Převede objekt na konkrétní typ.
type: docs
weight: 53
url: /cs/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metoda

Převede objekt na konkrétní typ.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) k převodu. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, na který převést. |

### Návratová hodnota

Převedený objekt.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) metoda

Převede objekt na konkrétní typ.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informace o kontextu konverze. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura používaná při převodu objektů. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) k převodu. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Typ, na který převést. |

### Návratová hodnota

Převedený objekt.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [TypeInfo](../../../system/typeinfo/)
* Třída [TypeConverter](../)
* Třída [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Jmenný prostor [System::ComponentModel](../../)
* Knihovna [Aspose.Slides](../../../)
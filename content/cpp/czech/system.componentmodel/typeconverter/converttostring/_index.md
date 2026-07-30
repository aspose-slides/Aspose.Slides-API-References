---
title: ConvertToString()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Převede objekt na řetězec.
type: docs
weight: 79
url: /cs/system.componentmodel/typeconverter/converttostring/
---
## TypeConverter::ConvertToString(const System::SharedPtr\<System::Object\>\&) metoda

Převede objekt na řetězec.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<System::Object> &value)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) k převodu. |

### Návratová hodnota

Převedený objekt.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) metoda

Převede objekt na řetězec.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informace o kontextu převodu. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) k převodu. |

### Návratová hodnota

Převedený objekt.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) metoda

Převede objekt na řetězec.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informace o kontextu převodu. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura, která se použije při převodu objektů. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) k převodu. |

### Návratová hodnota

Převedený objekt.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Object](../../../system/object/)
* Třída [TypeConverter](../)
* Třída [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Třída [CultureInfo](../../../system.globalization/cultureinfo/)
* Jmenný prostor [System::ComponentModel](../../)
* Knihovna [Aspose.Slides](../../../)
---
title: ConvertToString()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar objekt till sträng.
type: docs
weight: 79
url: /sv/system.componentmodel/typeconverter/converttostring/
---
## TypeConverter::ConvertToString(const System::SharedPtr\<System::Object\>\&) metod


Konverterar objekt till sträng.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<System::Object> &value)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) att konvertera. |

### Returvärde

Konverterat objekt.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) metod


Konverterar objekt till sträng.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) konverteringskontextinformation. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) att konvertera. |

### Returvärde

Konverterat objekt.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) metod


Konverterar objekt till sträng.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) konverteringskontextinformation. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur som används när objekt konverteras. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) att konvertera. |

### Returvärde

Konverterat objekt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [Object](../../../system/object/)
* Klass [TypeConverter](../)
* Klass [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Namnrymd [System::ComponentModel](../../)
* Bibliotek [Aspose.Slides](../../../)
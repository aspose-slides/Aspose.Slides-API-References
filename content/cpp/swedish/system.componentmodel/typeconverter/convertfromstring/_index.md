---
title: ConvertFromString()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar sträng till objekt.
type: docs
weight: 40
url: /sv/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) metod

Konverterar sträng till objekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Värde att konvertera. |

### Returvärde

konverterat objekt.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) metod

Konverterar sträng till objekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) konverteringskontextinformation. |
| text | const [System::String](../../../system/string/)\& | Värde att konvertera. |

### Returvärde

konverterat objekt.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) metod

Konverterar sträng till objekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) konverteringskontextinformation. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur att använda vid konvertering av objekt. |
| text | const [System::String](../../../system/string/)\& | Värde att konvertera. |

### Returvärde

konverterat objekt.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [String](../../../system/string/)
* Klass [TypeConverter](../)
* Klass [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Klass [CultureInfo](../../../system.globalization/cultureinfo/)
* Namnrymd [System::ComponentModel](../../)
* Bibliotek [Aspose.Slides](../../../)
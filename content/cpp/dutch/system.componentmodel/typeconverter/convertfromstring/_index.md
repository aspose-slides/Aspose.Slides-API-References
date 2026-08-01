---
title: ConvertFromString()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een string naar een object.
type: docs
weight: 40
url: /nl/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) methode

Converteert string naar object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Waarde om te converteren. |

### Retourwaarde

geconverteerd object.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) methode

Converteert string naar object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) conversiecontextinformatie. |
| text | const [System::String](../../../system/string/)\& | Waarde om te converteren. |

### Retourwaarde

geconverteerd object.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) methode

Converteert string naar object.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) conversiecontextinformatie. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultuur die te gebruiken is bij het converteren van objecten. |
| text | const [System::String](../../../system/string/)\& | Waarde om te converteren. |

### Retourwaarde

geconverteerd object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [String](../../../system/string/)
* Klasse [TypeConverter](../)
* Klasse [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Klasse [CultureInfo](../../../system.globalization/cultureinfo/)
* Naamruimte [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)
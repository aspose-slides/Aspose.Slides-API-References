---
title: ConvertToString()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Konwertuje obiekt na ciąg znaków.
type: docs
weight: 79
url: /pl/system.componentmodel/typeconverter/converttostring/
---
## TypeConverter::ConvertToString(const System::SharedPtr\<System::Object\>\&) metoda

Konwertuje obiekt na ciąg znaków.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<System::Object> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) do konwersji. |

### Wartość zwracana

Skonwertowany obiekt.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Object\>\&) metoda

Konwertuje obiekt na ciąg znaków.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Object> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje o kontekście konwersji. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) do konwersji. |

### Wartość zwracana

Skonwertowany obiekt.

## TypeConverter::ConvertToString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) metoda

Konwertuje obiekt na ciąg znaków.

```cpp
System::String System::ComponentModel::TypeConverter::ConvertToString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje o kontekście konwersji. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana podczas konwersji obiektów. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) do konwersji. |

### Wartość zwracana

Skonwertowany obiekt.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeConverter](../)
* Klasa [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System::ComponentModel](../../)
* Library [Aspose.Slides](../../../)
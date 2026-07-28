---
title: ConvertFromString()
second_title: Aspose.Slides dla C++ – Odwołanie API
description: Konwertuje ciąg znaków na obiekt.
type: docs
weight: 40
url: /pl/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) metoda


Konwertuje ciąg znaków na obiekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Wartość do konwersji. |

### Wartość zwracana

przekonwertowany obiekt.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) metoda


Konwertuje ciąg znaków na obiekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje o kontekście konwersji. |
| text | const [System::String](../../../system/string/)\& | Wartość do konwersji. |

### Wartość zwracana

przekonwertowany obiekt.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) metoda


Konwertuje ciąg znaków na obiekt.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informacje o kontekście konwersji. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultura używana przy konwersji obiektów. |
| text | const [System::String](../../../system/string/)\& | Wartość do konwersji. |

### Wartość zwracana

przekonwertowany obiekt.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [String](../../../system/string/)
* Klasa [TypeConverter](../)
* Klasa [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Klasa [CultureInfo](../../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System::ComponentModel](../../)
* Biblioteka [Aspose.Slides](../../../)